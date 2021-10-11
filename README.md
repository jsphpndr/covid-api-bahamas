# COVID-19 API Bahamas

This is a read-only, public API is an open-source project created by [https://josephpinder.com](Joseph Pinder) to make The Government of The Bahamas' COVID-19 Reports available and accessible for data presentation, manipulation and analysis.

## Contribution

This is a labour of love so, I'm looking for volunteers. Contributors to assist in the completion of this API. 

Any help is welcome. 

Below you will find the necessary details to get started.

## Technology

The API is generated with HUGO, a Golang static site generator (SSG).

### Tutorials

For help with HUGO installation if you don't already have it, you can follow Mike Dane's (@mikedane) tutorial on YouTube for installation and basic knowledge.

#### Mike Dane's Hugo - Static Site Generator | Tutorial

[![Mike Dane's Hugo - Static Site Generator | Tutorial](https://img.youtube.com/vi/qtIqKaDlqXo.jpg)](https://youtube.com/playlist?list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3)


#### Mike Dane's YAML | In One Video
[![Mike Dane's YAML | In One Video](https://img.youtube.com/vi/cdLNKUoMc6c.jpg)](https://youtu.be/cdLNKUoMc6c)


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

Any questions, please contact me [https://josephpinder.com/get-in-touch] (here).

## Checked Out

Reports are numbered from 564 - 1.

Put your name or don't but let others know what sequence you're taking out so no one is doing unnecessary, double work.

Edit this README.md and list your report or report series below.

[//]: # (If you're reading this, you're checking out. List the report or reports that you'll be completing.)

560 - 515

## Contributors

I'd like to highlight those contributing, please feel free to list your name linked to (or along with a link) to your site or social account and the report or report series that you completed.

Please do this by adding your name and report or report series to the `index.html` file in the `layouts` directory.