[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=11521498)
# Sphinx Profile Page

This is is a template for a resume/ personal portfolio, built with Sphinx! Based on [Chris Holdgraf's personal site](https://github.com/choldgraf/choldgraf.github.io)

This template is designed for use in the URI CS TD SSP. 


## Tips for Updating the Content of this site

- sidebar variables are defined in `info-.yml` 
- sidebar formatting for sidebar is in `_templates/hello.html` 
- variables are used via `html_context`
- get social links back by removing setting to `navbar_end` in `conf.py` and set values by [example](https://github.com/choldgraf/choldgraf.github.io/blob/main/conf.py#L41)


## To work with this repo offline (or in codespaces)

**This requires having python installed then installs a package that helps build the website**

The easiest way to build the website is to use `nox`, which handles all of the environment generation automatically.
To do so, follow these steps:

1. Install `nox`.

   ```shell
   pip install -U nox
   ```
2. To run a live webserver that will auto-build and reload when you make changes, run:

```shell
nox -s docs-live
```

If on Codespaces, use accept the port forwarding and open the forwarded port in a new browser tab to preview your site while you work. 

<!-- 
Run `nox`

   ```shell
   nox -s docs
   ```

this should install a Sphinx environment and build the site, putting the output files in `_build/html`. -->
# Profile Website

Welcome to my profile webiste, Students and Faculty Members of TD
<!-- enter your target audience after the comma above -->

Since you're here, you might be wondering who I am and what I will be majoring in, you will also see photos of me during TD and all my work. You will see step by step on how I completed on making a website during Talent Development. 
<!-- make a bulleted list of 3 fictional visitors to your site. Include a few detials about them that could impact how you design for them. For each visitor, assign a task or goal they have for visiting your profile website -->

## Design 

Showing others how effiecnt my website is for it being the first time coding this. I want to show others what I will be doing this upcoming semester and how I am preparing for it by being in this CSC class. I want to show this by using photos and graphs that we have done during  this class so others can see what the power of coding can do and how effiecnt it is. This project can be used for future projects which can help me in other work.

## Accessibility 

I want to make the color palette and word font good enough for everyone to see as some people may not be able to see it or may have due colorblindess or bad vision. I will do this by changing my website format. 
