# ash-cv

CV for Ashley Hindmarsh, Director and Chief Consultant/Engineer for Belle Software (UK)
Should be built and deployed via travis-ci.org

I wanted a create CV which I could maintain in Markdown format, and distribute in multiple formats (PDF/Word/HTML) to meet the (fickle) demands of agencies who still only accept CVs in Word format.

Please copy/share as you see fit, but please respect the copyright of Steve Klabnik, whose script I hijacked.

To build CVs locally for testing, try this (Unix/Docker reqd)

    docker pull pandoc/latex:2.6
    make all
