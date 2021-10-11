# COVID-19 API Bahamas

This is a read-only, public API is an open-source project created by [Joseph Pinder](https://josephpinder.com) to make The Government of The Bahamas' COVID-19 Reports available and accessible for data presentation, manipulation and analysis.

## Contribution

This is a labour of love so, I'm looking for volunteers. Contributors to assist in the completion of this API. 

Any help is welcome. 

Below you will find the necessary details to get started.

## Technology

The API is generated with HUGO, a Golang static site generator (SSG).

### Tutorials

For help with HUGO installation if you don't already have it, you can follow Mike Dane's (@mikedane) tutorial on YouTube for installation and basic knowledge.

#### Mike Dane's Hugo - Static Site Generator | Tutorial

[![Mike Dane's Hugo - Static Site Generator | Tutorial](https://i3.ytimg.com/vi/qtIqKaDlqXo/hqdefault.jpg)](https://youtube.com/playlist?list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3)


#### Mike Dane's YAML | In One Video
[![Mike Dane's YAML | In One Video](https://i3.ytimg.com/vi/cdLNKUoMc6c/hqdefault.jpg)](https://youtu.be/cdLNKUoMc6c)


## Data Entry

If you're contributing, there are vary few files to be tampered with.

You will be dealing with the `contents/reports` directory only. 

## Creating An Entry

To create a new report:

```
hugo new reports/{{report.number}}.md
```

A new file will be created.

For example, if your file is 343, then your result should be `reports/343.md`.

## Entering Data

Using the `hugo new` will populate the necessary fields to be updated.

You will find your newly created file well commented.

Feel free to use the ad hoc variable library to speed up the process of filling in island name and sex values.

The flow of the report file corresponds in the reading manner of the physical report, left to right.

Once done, check your work, save, commit and submit a merge request.

Any questions, please contact me [here](https://josephpinder.com/get-in-touch).


## Finding The Resource

You can locate the series of reports for 2021 listed here [here on the government website](https://www.bahamas.gov.bs/wps/portal/public/News/!ut/p/b1/vZPZrqM4FEW_5X4AFzPDIyFMAcxgM75EIRNjJkgc-PrKbZXUVS1Vqh-62ufJ0jreOnsf0wWd0cVp86iPm7E-nzbd170Q1xwwPVXlZc8UgAjsOHDVQLJYnxFeQP4CwC-OCt72Oyyd0hng16gBN9-Z2vO004JkmREl27s7WQoccIIOozOTilGU9ZfQKOzoetX2HF-0q63btUZPiWlqiMNGVH3oxJWHAbNyt4I3k2BuG4gVzcezx8BYsb05C-Ey8eFOB0ODnsCNn1g_pXhpTxgbgQc6By0LF2wndrJUK0_5sv8-45sh_pVHvwJ48Lv-lC7eIl8v_AW8i-F3QUDr3O_p_IVJP2A4AcBmgBohJgQyZGj8Pa_pYs_tHDWATHDeQYQ9AOYY4GWGYPkyd9QYT2dWjA4mT-e_zHURaFkE3WCXRPFC1Shf39z-KeizWHkJaozoxAJAgP_Tgqbgyy8jJByoAgtMn_m_BbkvwSZnFjXvEd3O1lPHy0UDV43dKyg1u4Wy0-7TU9TyvhjPRlIr55S6jxkismIcy_1enkoqraDI8mDEtibXrpt3XDuMiFCJJZUoFwQnJg_qoZU-iAKBDQlcTG198dBqJp1Zd4FuuvZ9A6tnONyieneahTsc1sTqLXVDHR88cDfV4VFCtw3nliOjtXJQphy1VPf8vMO3c59ylW2Rtj9YFlmWfXeoHpo1umdG2l-Gi-Jdj1dX9u53qpe00j7W87Li_PK01hppWs_XTikNSYGKZGpmfXtitwjYpFkS9ePtipiBD_54Yj99Aj7873dyRRd12X-Sbf8JPmVFZARJ5hVZBDwvS3TS5EBayvZrO4K1NtyhYgp9CGoiG8c8rPbxeN4iB1FdxARUsNGHRp-pUh9Y50aKtgwXan3toFvOOJIV4D93pm2g5hiEZz1zndkILR4S3SRZr8YJ8PvpQVGUX2hjf4TZvbrsrf0qPiXUJpuF-boPeI57VGU7mVuJCbx8ZJOC2g0ch9LDELEiNm4mw0cGOuQZxtvDYAbXsYLHjw_60scPxxUjizDy30U-vgFGyZfh/dl4/d5/L2dBISEvZ0FBIS9nQSEh/).

Reports are listed in globs, i.e. "COVID-19 Report Update #547 - #553".

It takes a little initiative, especially, with the government's site constantly crashing. Just remember: "Labour of love". Lots of love.

Older listings from 2020 are found [here](https://www.bahamas.gov.bs/wps/portal/public/novel%20coronavirus%20(2019-ncov)/!ut/p/b1/vZTLjqMwEEW_pT-AxjwCzpI3IeAEsCGwQQTIg0CTBhIeXz9pTUuz6sxmJq6VpXt9VFdVpmN6R8cf6f18TPtz85FWX_dYSDhj47gKDx0o8EuwYjBaqdqWMzjmIYgeAvDDkcBvPzAcSXr4Nyz-8iuMsCYLAFWBDumdGc222jhHXfOS0WWs2yQdgZaGhya-1V2vXpXL7rjAd5sjTAb5y8CkbPg5mlxeKYXT7ic27czz_dSFubxLloI1zxem1HMt2VNGONyM1NRhyZo1pZTX-jTfREQVRB3mKxx5jbCbNo3ETJcVwn_IRAkCbfnZ6zIxii47ylTFKCMSk4uJuyAtpbe3756fNPWXzEI6fh4L_y14Eisym7qgo4dM_PEdGdCY3gE-8cvpupovs1eCce3MwQqp2gRsMvhkJghrrJMj1JXuBHBg-ZeF5ZPRQdhl-x5v88AjsqTIFe-Vz4G-LbwWCGXm1UDxvwPXLPcA2pyNoML4BvdiIPz3Q2PR8Xlfvw9Z_Q7e4ZJjlwsRQB4yCwYwdFBGwqh2q0HTUHIqyMVATba3lREORqWAFleat84qfcLZ_aBN13o0sFjsZd2iBGMT8JIU51VacMcQkCLbklvsKFEquZlFespz2WZtSxt726JWGQRXSzAPO3mfE4JMapB2o_-Z6_fHZhei51ZKa0doc8iTBpvZ6JAq2vIirM-ncUL4HqyvDvaDGJgxExL_0HTUuYyRGjuW3R4KQczamuqn_jbS15rcbcGD6PCnnMfn8QvP958K/dl4/d5/L2dBISEvZ0FBIS9nQSEh/).

Good luck and Godspeed.

## Checked Out

Reports are numbered from 564 - 1.

Put your name or don't but let others know what sequence you're taking out so no one is doing unnecessary, double work.

Edit this README.md and list your report or report series below.

[//]: # (If you're reading this, you're checking out. List the report or reports that you'll be completing.)

560 - 515

## Contributors

I'd like to highlight those contributing, please feel free to list your name linked to (or along with a link) to your site or social account and the report or report series that you completed.

Please do this by adding your name and report or report series to the `index.html` file in the `layouts` directory.