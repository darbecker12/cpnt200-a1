# CPNT200
Assignment - 1 Client site profile
Darryl Becker
500px

## Client Summary
Company Name: 500px

Company Industry: Photography Sharing

Website URL: https://500px.com/

Target Audience: Photographers and photography viewing

What is their proposition? 500px is a image sharing website that allows photographers to show their images. When uploading their image, photographers are also able to share the camera, lense and the settings used to take the image.

What are they selling? 500px also does photo licensing so that photographers are able to sell their images. AlCompany Name: 500px
Company Industry: Photography Sharing
Website URL: https://500px.com/
Target Audience: Photographers and photography viewing
What is their proposition? 500px is a image sharing website that allows photographers to show their images. When uploading their image, photographers are also able to share the camera, lense and the settings used to take the image.alytical data. Data like how many people are viewing their images, the amount of people viewing their profile and more is able to be viewed with a membership.

### Single Types
- Home Page
  - Fields:
    - Title: Medium Text
    - Description: Rich Text
    - Secondary Title: Small Text
    - Secondary Description: Rich Text
    - Category (Galleries): Relation - many-to-many  

    

### Collection Types

- Photographer Profile
 - Fields: 
  - Location: Location
  - Social Media: Component
                    - Instagram
                    - Twitter
                    - Website
  - Galleries: Enumeration
  - Licensing: Relation - one-to-many
  - Gallery: Relation - one-to-many

- Photo
  - Fields:
    - Location: Location
    - Taken: Date
    - Uploaded: Date
    - Description: Rich Text
    - Image Details: Component
                      - Camera - Small Text
                      - Lense - Small Text
                      - Focal Range - Small Text
                      - F-Stop - Small Text
                      - Shutter Speed - Small Text
                      - ISO - Small Text
    - Category: Enumeration

- Discover
  - Fields:
    - Categories: Component
                    - Popular - Small Text
                    - Upcoming - Small Text
                    - Fresh - Small Text
                    - Editors' Choice - Small Text
                    - Galleries - Small Text
                    - Resource Hub - Small Text
    - Gallery: Relation - many-to-many
    - Hover Effect: Component:
                      - Photographer - Small Text
                      - Pulse - Number
                      - Like - icon
                      - Ellipsis - icon
- Resources
  - Fields: 
    - Categories: Component
                    - Home - Small text and icon
                    - Discover - Small text and icon 
                    - Upload - Small text and icon
    - Search Bar: Relation - One-to-many
    - Description and Learn more - Small Text
    - Featured Resources: Component:
                            - View All
                            - Resouce: component:
                              - Title: Small Text
                              - Type: Enumeration
                              - Where: Enumeration
                              - Price: Number
                              - Author: Small Text
    - Starting Soon: Component:
                        - View All
                        - Resouce: component:
                          - Title: Small Text
                          - Type: Enumeration
                          - Where: Enumeration
                          - Price: Number
                          - Starting Date: Date
                          - Author: Small Text
    - Article: Component:
                  - View All
                  - Resouce: component:
                    - Title: Small Text
                    - Type: Enumeration
                    - Where: Enumeration
                    - Price: Number
                    - Author: Small Text

  - Blog
    - Fields:
      - Hero Section: Component:
                        - Image: image
                        - Featured Article: Coloured Small Text
                        - Title: Medium Text
                        - Published by: Author
                        - Description: Small Text
                        - Social Media: Icons
      - Top Posts: Medium Text
      - Blog Posts: Component:
                      - Image: image
                      - Author: Small Text
                      - Description: Small Text
                      - Keep Reading: Button - Relation: one-to-one


## Adapt and Critique
I believe the the site is structured in a way that after some time on the website, a user can find all of what they are looking for. Overall, the website has a lot of information and a lot to look at but I feel like it is a little bit hard at first to really find what you are looking for. 

Many aspects of this website could be improved like having all of the navigation bar viewable to the user instead of having to click on the ellipses to view more navigation bar links. This is an issue because if a user is looking for something that is hidden, they might not think about clicking the ellipses to find what they want to view. Another aspect that could be improved would be clicking a single time to view the popular images instead of having to click on the discover link in the nav bar and then having to click once more. This along with having an option to view the popular images in the main page of the website. This issue makes the website slower to navigate.

People would choose this site over another company if they want to find many different pictures without having to deal with a lot of advertisements. For photographers, this site allows any image and it also has a section to put the settings of the camera for people that want to share that information or for the people that are interested in it.

This website relates to my strapi project because I want to create a space for poeple to upload images without any boundaries along with not having to deal with many rules when uploading images.


