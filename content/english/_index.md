---
############################### Banner ##############################
banner:
  enable: true
  bg_image: "images/slider-bg.jpg"
  bg_overlay: true
  title: "Website about documentation <br/> & Why it matters"
  content: "We love technical documentation"
  button:
    enable: true
    label: "Discover Our Tutorials"
    link: "project"

############################# About #################################
about:
  enable: true
  title: "About DocsMatter"
  description: "The DocsMatter website provides some resources for creating good technical documentation."
  content: "Here you can find information about modern technical writing tools and approaches, including docs like code, Markdown, AsciiDoc, static site generators (Hugo, Sphinx, and Gatsby), technical documentation sites, documentation standards (e.g. XML and DITA), and so on. You will also learn about other technical documentation-related topics like translation management and video editing."
  image: "images/wrapper-img.png"


######################### Portfolio ###############################
portfolio:
  enable: true
  bg_image: "images/feature-bg.jpg"
  title: "Technologies behind this website"
  content: "This website was built using the Hugo static site generator. For storing and delivering the site's static content, Amazon Simple Storage Service (S3) and Amazon CloudFront (CDN) are used.


  The content is created in Markdown, a lightweight markup language that can be written with any plain-text editor. As an editor, we use Visual Studio Code providing support for Markdown text out of the box.


  All source files are stored in a local Git repository.
  "
  button:
    enable: true
    label: "Read more"
    link: "blog"


############################# Service ############################
service:
  enable: true
  # service content comes from "service.md" file


############################ call to action ###########################
cta:
  enable: true
  bg_image: "images/call-to-action-bg.jpg"
  title: "We design delightful digital experiences."
  content: "Read more about what we do and our philosophy of design. Judge for yourself The work and results <br> we’ve achieved for other clients, and meet our highly experienced Team who just love to design."
  button:
    enable: true
    label: "Tell Us Your Story"
    link: "contact"

############################# Funfacts ###############################
funfacts:
  enable: true
  title: "Fun Facts About Us"
  description: "'Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, <br> there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics'"
  funfact_item:
  # funfacts item loop
  - icon: "ion-ios-chatboxes-outline" #ionicon pack v2: https://ionicons.com/v2/
    name: "Cups Of Coffee"
    count: "99"
    
  # funfacts item loop
  - icon: "ion-ios-glasses-outline" #ionicon pack v2: https://ionicons.com/v2/
    name: "Article Written"
    count: "45"
    
  # funfacts item loop
  - icon: "ion-ios-compose-outline" #ionicon pack v2: https://ionicons.com/v2/
    name: "Projects Completed"
    count: "125"
    
  # funfacts item loop
  - icon: "ion-ios-timer-outline" #ionicon pack v2: https://ionicons.com/v2/
    name: "Combined Projects"
    count: "200"

  testimonial_slider:
  # testimonial item loop
  - name: "Raymond Roy"
    image: "images/clients/avater-1.jpg"
    designation: "CEO-Themefisher"
    content: "This Company created an e-commerce site with the tools to make our business a success, with innovative ideas we feel that our site has unique elements that make us stand out from the crowd."
              
  # testimonial item loop
  - name: "Randi Renin"
    image: "images/clients/avater-1.jpg"
    designation: "CEO-Themefisher"
    content: "This Company created an e-commerce site with the tools to make our business a success, with innovative ideas we feel that our site has unique elements that make us stand out from the crowd."
              
  # testimonial item loop
  - name: "Rose Rio"
    image: "images/clients/avater-3.jpg"
    designation: "CEO-Themefisher"
    content: "This Company created an e-commerce site with the tools to make our business a success, with innovative ideas we feel that our site has unique elements that make us stand out from the crowd."


---