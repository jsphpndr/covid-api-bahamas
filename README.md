# COVID-19 API Bahamas

This open-source project was created by [Joseph Pinder](https://josephpinder.com) as a read-only public API to make the Government of The Bahamas' COVID-19 reports available and accessible for data manipulation, analysis and presentation.

> co-authored by [Sowmya Thottambeti](https://www.linkedin.com/in/sowmyathottambeti/)


# How To Contribute

Since this is an open-source project, we are relying on the community's assistance. If you would like to contribute, continue reading the instructions below.

### Technology

This API is generated with HUGO, a Golang static site generator (SSG).

### Basic Installation

If you don't have HUGO already installed on your machine, you may follow Mike Dane's (@mikedane) tutorials on how to install it.


#### 1) [Mike Dane's Hugo - Static Site Generator | Tutorial](https://youtube.com/playlist?list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3)


#### 2) [Mike Dane's YAML | In One Video](https://youtu.be/cdLNKUoMc6c)

### Git Tutorials

For non-coders, in addition to HUGO there's an additional knowledge requirement of Git.

Git is the means by which we access this Github repository to push (upload) and pull (download).

If you want to help out, you will need one or all of the following tutorials.


#### 4) [Git and GitHub for Beginners - Crash Course](https://youtu.be/RGOj5yH7evk) *(Recommended)*
#### 1) [Git Tutorial for Beginners: Command-Line Fundamentals](https://youtu.be/HVsySz-h9r4)
#### 1) [Git Tutorial for Beginners: Learn Git in 1 Hour](https://www.youtube.com/watch?v=8JJ101D3knE)
#### 3) [Learn Git In 15 Minutes](https://www.youtube.com/watch?v=USjZcfj8yxE)

### Forking the Repo.

On the top right corner of this repository, click the "Fork" button. By doing this, you will have your own copy of the repository and may freely experiment without affecting the original repository.

### Cloning the Repo.

Let's navigate to **your** version of the repository. This can be found on your profile under the list of repositories -- look for *covid-api-bahamas*.

Clone the repository on your local machine by running the following command: `git clone <https url>`. The *https url* value can be found by clicking the green dropdown with the word 'Code' on it, simply pressing 'HTTPS' and copying the url below that.

From the main branch, create a separate working branch. This can be done by running `git checkout -b <branchName>`. If your file is 343, your branch name would be *report/343*. If you would like to do a range of files, i.e. 343 - 350, your branch name would then be *report/343-350*.

You may see which files have been done already by evaluating the [active pull requests](https://github.com/jsphpndr/covid-api-bahamas/pulls) and viewing the [reports directory](https://github.com/jsphpndr/covid-api-bahamas/tree/main/content/reports). Only select files which are free to take.

Create a new remote for the upstream repository by running `git remote add upstream https://github.com/jsphpndr/covid-api-bahamas`

Now, time to create an entry!


### Creating a Data Entry

You will only be dealing with the `contents/reports` directory. 

To create a new report, run the following command: `hugo new reports/{{report.number}}.md`

Running the previous command will create a new file report. For example, if your file is 343, then the result should be `reports/343.md`. You may see which reports have been done already by evaluating the active branches and viewing the [reports directory](https://github.com/jsphpndr/covid-api-bahamas/tree/main/content/reports)


### Entering the Data

Running the command, `hugo new` will populate the necessary fields to be updated.

You will find your newly created file well commented. Feel free to use the ad hoc variable library to speed up the process of filling in island name and sex values.

The flow of the report file corresponds in the reading manner of the physical report, left to right.

### Contributions

We would also like to highlight you and the contribution that you made to this API. 

Navigate to `data/contributors.yml` and follow the instructions there to add your name, and optionally, link to your personal or company website or social media page.

#### Where to find your name?

If you entered your name in `data/contributors.yml` your name will be featured on the homepage.

As a plus, if you add your name (and link) to the report file, it will be featured on the report page as follows:

```
Report 000 contributed by Your Name.
```

Make it a moment to shine and add something nice to the résumé.

### Committing the Changes

After a self review ensuring that you have sucessfully followed the above steps, you are now ready to push your code.

In order to commit the new code, run the following code: `git add .` & `git commit -m <message>`. Your message should be 'report 343 by <your name here>' so, in my case, I would put 'report 343 by Sowmya Thottambeti'. 
  
Once this is done, a simple `git push` should do the trick. If there is no upstream branch, you may have to use `git push --set-upstream origin <branchName>`
  
### Pull Request
  
On the forked GitHub repo, create a pull request wherein you would merge your forked version into the original main branch. The title of your pull request should be 'report 343 by <your name here>' so, in my case, I would put 'report 343 by Sowmya Thottambeti'. 
  
A member from our team will review the pull request and if everything was done correctly, we will gladly merge it into the main branch.


# Resource

You may locate the series of reports for the year 2021 on the government's [website](https://www.bahamas.gov.bs/wps/portal/public/News/!ut/p/b1/vZPZrqM4FEW_5X4AFzPDIyFMAcxgM75EIRNjJkgc-PrKbZXUVS1Vqh-62ufJ0jreOnsf0wWd0cVp86iPm7E-nzbd170Q1xwwPVXlZc8UgAjsOHDVQLJYnxFeQP4CwC-OCt72Oyyd0hng16gBN9-Z2vO004JkmREl27s7WQoccIIOozOTilGU9ZfQKOzoetX2HF-0q63btUZPiWlqiMNGVH3oxJWHAbNyt4I3k2BuG4gVzcezx8BYsb05C-Ey8eFOB0ODnsCNn1g_pXhpTxgbgQc6By0LF2wndrJUK0_5sv8-45sh_pVHvwJ48Lv-lC7eIl8v_AW8i-F3QUDr3O_p_IVJP2A4AcBmgBohJgQyZGj8Pa_pYs_tHDWATHDeQYQ9AOYY4GWGYPkyd9QYT2dWjA4mT-e_zHURaFkE3WCXRPFC1Shf39z-KeizWHkJaozoxAJAgP_Tgqbgyy8jJByoAgtMn_m_BbkvwSZnFjXvEd3O1lPHy0UDV43dKyg1u4Wy0-7TU9TyvhjPRlIr55S6jxkismIcy_1enkoqraDI8mDEtibXrpt3XDuMiFCJJZUoFwQnJg_qoZU-iAKBDQlcTG198dBqJp1Zd4FuuvZ9A6tnONyieneahTsc1sTqLXVDHR88cDfV4VFCtw3nliOjtXJQphy1VPf8vMO3c59ylW2Rtj9YFlmWfXeoHpo1umdG2l-Gi-Jdj1dX9u53qpe00j7W87Li_PK01hppWs_XTikNSYGKZGpmfXtitwjYpFkS9ePtipiBD_54Yj99Aj7873dyRRd12X-Sbf8JPmVFZARJ5hVZBDwvS3TS5EBayvZrO4K1NtyhYgp9CGoiG8c8rPbxeN4iB1FdxARUsNGHRp-pUh9Y50aKtgwXan3toFvOOJIV4D93pm2g5hiEZz1zndkILR4S3SRZr8YJ8PvpQVGUX2hjf4TZvbrsrf0qPiXUJpuF-boPeI57VGU7mVuJCbx8ZJOC2g0ch9LDELEiNm4mw0cGOuQZxtvDYAbXsYLHjw_60scPxxUjizDy30U-vgFGyZfh/dl4/d5/L2dBISEvZ0FBIS9nQSEh/).

Reports are listed in globs, i.e. "COVID-19 Report Update #547 - #553".

Older listings from the year 2020 are found [here](https://www.bahamas.gov.bs/wps/portal/public/novel%20coronavirus%20(2019-ncov)/!ut/p/b1/vZTLjqMwEEW_pT-AxjwCzpI3IeAEsCGwQQTIg0CTBhIeXz9pTUuz6sxmJq6VpXt9VFdVpmN6R8cf6f18TPtz85FWX_dYSDhj47gKDx0o8EuwYjBaqdqWMzjmIYgeAvDDkcBvPzAcSXr4Nyz-8iuMsCYLAFWBDumdGc222jhHXfOS0WWs2yQdgZaGhya-1V2vXpXL7rjAd5sjTAb5y8CkbPg5mlxeKYXT7ic27czz_dSFubxLloI1zxem1HMt2VNGONyM1NRhyZo1pZTX-jTfREQVRB3mKxx5jbCbNo3ETJcVwn_IRAkCbfnZ6zIxii47ylTFKCMSk4uJuyAtpbe3756fNPWXzEI6fh4L_y14Eisym7qgo4dM_PEdGdCY3gE-8cvpupovs1eCce3MwQqp2gRsMvhkJghrrJMj1JXuBHBg-ZeF5ZPRQdhl-x5v88AjsqTIFe-Vz4G-LbwWCGXm1UDxvwPXLPcA2pyNoML4BvdiIPz3Q2PR8Xlfvw9Z_Q7e4ZJjlwsRQB4yCwYwdFBGwqh2q0HTUHIqyMVATba3lREORqWAFleat84qfcLZ_aBN13o0sFjsZd2iBGMT8JIU51VacMcQkCLbklvsKFEquZlFespz2WZtSxt726JWGQRXSzAPO3mfE4JMapB2o_-Z6_fHZhei51ZKa0doc8iTBpvZ6JAq2vIirM-ncUL4HqyvDvaDGJgxExL_0HTUuYyRGjuW3R4KQczamuqn_jbS15rcbcGD6PCnnMfn8QvP958K/dl4/d5/L2dBISEvZ0FBIS9nQSEh/).


# Contact
For any questions and/or concerns, feel free to fill out the [form](https://josephpinder.com/get-in-touch).
