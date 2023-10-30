# Changelog

## v1.0.0

### Added or Changed
- First release of scripts. 
- Working Sections:
    - Scrape class schedule for current and next week (using Selenium).
    - Parse class schedule HTML into a list of custom class objects.
    - Book class (given date and custom generated class id) using Selenium. 

### TODO
- Move functions to different files for cleanliness. 
- Look into using a combination of requests and Selenium for faster scraping and booking.
    - (Scraping (10) + Booking (20)) currently takes ~30 seconds (could be longer with heavy traffic). 
- Create a web front-end. 
- Add email confirmation for successful booking.
    - Add calendar invite file to email. 