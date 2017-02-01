# HackSC Fall 2017

This is the first HackSC for which we will build a series of open sourced hackathon-enhancing tools. Our goal is to make the tools we build for this event maintainable and re-usable for every HackSC thereafter. In order to meet this goal, we will strive to do two things:

1. Provide fully documented code
2. Modularize every tool

The code in this repository is a set of purely frontend React components. We do this under the assumption that the website and the branding will differ so much in future hackathons that completely new designs and components will be created. Assuming that our system of modularization is structured well, it should be relatively easy for the future developer of HackSC's website to swap out components and keep most functionality the same. Therefore, instead of building the website alongside the server, we will separate the view from the controller completely. These components will then be plugged into what the server serves publicly, connected to the models in our infrastructure, with some required tweaks.
