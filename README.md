# barcampgr-2019-3D-print-signup
This is a signup sheet for people requesting 3D prints at BarCamp GR 2019

Thanks to Danny Markov for creating the form template files found here: https://tutorialzine.com/2015/07/freebie-7-clean-and-responsive-forms

I would have loved to make it from scratch but we only had 10 days to get it up and working.
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

The idea of the project is to setup a print station where we can showcase 3D printing. We'll have a web form on an iPad that allows someone to select 1 model they want 3D printed and that data gets stored, then displayed on an admin webpage that we can view.

When the request is processed, the webpage logic uses a stored size value (example: model A is 30% of printer build plate, model C is 15%, etc.) to determine if that selected model has enough room on the build plate to be part of that batch of prints. If it doesn't, then the logic will assign it to the next printing batch and it will begin tracking the new batch's availabe build plate space.

On the  Admin page, we'll see a list of all batchs, what model is assigned to it, and what the submitters name is (so we can call them out when the print is done/label the print).

The Admin page will require a login (or is this not needed?).

All devices and data will be stored on a local network that is temporarily setup. Hardware will be RaspPi computers running Ubuntu.
