<template lang="pug">
  div(id="app")
    div.head_wrapper
      div.head_text
        h1.head_title
          |Ionic App
          br
          |Development Company
        p.head_paragraph 
          |Ionic is the number one solution for startups at the MVP stage. 
          |It allows you to simultaneously build applications for multiple platforms using only web technologies. 
          |Reusing code enables you to quickly prove your concept and make frequent iterations even with a tight budget.
      img(src = "./assets/logo.svg").head_logo 

    div.reasons_wrapper
      h2.reasons_title Reasons to choose Ionic for your app
      div.reasons_container
        .reason
          h3 Use web technologies to build a mobile app
          p Ionic was initially based on Angular. But with Ionic 4+, you can build a mobile app using React and Vue.js as well.
        .reason
          h3 Reuse your web app code
          p If you have an existing web application, you can reuse much of the codebase to speed up mobile development.
        .reason
          h3 Share one codebase across all platforms
          p An Ionic application can be built once and run smoothly on any device with minimal modifications.
        .reason
          h3 Offer a near-native user experience
          p Even though it’s built with web technologies, an Ionic app feels like a real mobile application: it can be installed from an app store, has access to all native platform features, and looks just like a native app.

    div.specifics_wrapper
      .specifics_content
        h2.specifics_title Specifics of Ionic app development
        div.specifics_container
          .specific
            h3 Built-in and custom components
            p
              | Ionic provides a huge library of components you
              | can customize. You can also create brand-new
              | components if needed.
          .specific
            h3 Platform-specific styles
            p
              | Ionic uses modes to customize components
              | according to the platform the app is used on.
              | This helps you achieve a native-like user experience.
          .specific
            h3 Live reloads
            p
              | Ionic apps automatically reload in the browser or
              | WebView when changes are detected. This
              | enables faster development and easier testing.
          .specific
            h3 Testing
            p
              | When generated in the command-line interface,
              | an Ionic application is automatically set up for
              | unit testing and integration testing.

    div.industries_wrapper
        h2.industries_title Ionic development services are a perfect match for various industries
        div.industries_container
          .industry
            img.industry_img(src = "./assets/truck 1.svg")
            div.industry_text
              h3 Logistics
              p Order traking systems, barcode scanning, automatic, route planning software
          .industry
            img.industry_img(src = "./assets/manufacturer 1.svg")
            div.industry_text
              h3 Manufacturing
              p Inventory management system, ERP system, factory surveillance software
          .industry
            img.industry_img(src = "./assets/real 1.svg")
            div.industry_text
              h3 Real estate
              p Property management projects, augmented reality showing apps, lead nurturing software
          .industry
            img.industry_img(src = "./assets/retali 1.svg")
            div.industry_text
              h3 Retail
              p Stock management systems, order management software, barcode scanning apps
          .industry
            img.industry_img(src = "./assets/sale 1.svg")
            div.industry_text
              h3 E-commerce
              p Cross-platform online shops, CRM systems, order management systems
          .industry
            img.industry_img(src = "./assets/laptop 1.svg")
            div.industry_text
              h3 Marketplaces
              p Online marketplaces, CRM systems, payment gateways integrations
          .industry
            img.industry_img(src = "./assets/network 1.svg")
            div.industry_text
              h3 Internet of Things
              p Smart home, smart factory systems, connected medical devices
          .industry
            img.industry_img(src = "./assets/doctor 1.svg")
            div.industry_text
              h3 Hospitality
              p Reservation systems, hotel management software, hotel guests apps
          .industry
            img.industry_img(src = "./assets/car-service 1.svg")
            div.industry_text
              h3 Automotive
              p Navigation systems, connected car systems, autonomous cars software

    div.apps_wrapper
      h2.apps_title Ionic mobile apps we’ve developed for our clients
      div.apps_container
        .mobile_app
          img.app_img(src = "./assets/Group 131.svg")
          p.app_text
            strong Toddy 
            |is an online marketplace for babysitters and young parents that we developed using Ionic. Native plugins enable the app to access smartphone features. We also integrated Toddy with the Australian payment gateway Pin Payments system.
        .mobile_app
          img.app_img(src = "./assets/Group 144.svg")
          p.app_text
            strong WijnSpijs 
            |is a food tourism startup in the Netherlands. The company organizes gastronomical experiences for guests from different countries. The system we developed consists of two separate applications: one for guests and one for restaurants. Both are hybrid apps built with Ionic and Symfony (PHP).
        .mobile_app
          img.app_img(src = "./assets/Group 145.png")
          p.app_text
            strong Audalize 
            |is a streaming platform that allows businesses to play music and other audio files in public venues such as cafes, shops, and gyms. We built a web portal and mobile app for iOS and Android using Ionic 4, Angular 7, and Node.js. The platform is integrated with Spotify and Apple Music.

    div.offer_wrapper
      .offer_content
        .offer_text_block
          h2.offer_title What do we offer?
          div.offer_paragraph
            h2 01.
            p Ionic mobile app development for Android and iOS
          div.offer_paragraph
            h2 02.
            p Migration to Ionic web development
          div.offer_paragraph
            h2 03.
            p Full-cycle product development including business analysis, design, app development, and quality assurance
          div.offer_paragraph
            h2 04.
            p A dedicated team of Ionic developers to work on your mobile app and integrate it with web or desktop software
          div.offer_paragraph
            h2 05.
            p Support and upgrades of released hybrid applications
        div.offer_img_block
        img.offer_img(src = "./assets/our_team.jpg")

    div.why_choose_wrapper
      h2.why_choose_title Why choose Clockwise Software as your Ionic app development company?
      p.why_choose_text Our developers have been using Ionic since its release in 2013. Currently, we work with the latest Ionic 5.x since it perfectly matches the market requirements for mobile apps. Deep expertise in other domains allows us to deliver effective solutions for any business.
      a.why_choose_btn Tell us about your project 
        span &#8594;

    div.one_stop_shop_wrapper
      h2.one_stop_shop_title One-stop-shop for mobile and web development
      div.one_stop_shop_container
        .one_stop_shop_block
          img(src = "./assets/coding 1.svg")
          div.one_stop_shop_text
            h3 Ionic mobile app development
            p We build cross-platform mobile apps that run on any platform using only JavaScript — the most popular programming language in the world.
        .one_stop_shop_block
          img(src = "./assets/web-programming 1.svg")
          div.one_stop_shop_text
            h3 Ionic web development
            p Since Ionic code is reusable, we can carry out mobile and web development simultaneously, enabling us to release both web and mobile apps in the shortest time.

    div.achievements_wrapper
      h2.achievements_title Our Achievements
      div.achievements_container
        img(src = "./assets/image 5.svg")
        img(src = "./assets/image 4.svg")
        img(src = "./assets/Rectangle.svg")

    div.approach_wrapper
      div.approach_content
        .approach_text
          h2 We take a tailored approach to each project
          p At Clockwise Software, we involve various professionals in each project to achieve the best results. We’re ready to guide you through the following stages of product development:
        ul
          li Business analysis
          li Requirements definition
          li Budget optimization
          li Prototyping
          li MVP development and launch
          li Further product development in short iterations
          li Product support and maintenance

    div.clients_wrapper
      h2.clients_title Our clients
      .clients_container
        img(src = "./assets/Knocking-1.svg")
        img(src = "./assets/Johnson.svg")
        img(src = "./assets/Knocking.svg")
        img(src = "./assets/EmailMeForm.svg")
        img(src = "./assets/rainforest_logo_gray 1.svg")

    div.join_wrapper
      .join_text
        h2 Will you join the club of the most innovative companies?
        p Are you ready to start developing a world-class Ionic app? Our team is ready to turn your idea into reality.
      form.join_form
        div.first_last_name
          input(type="text" placeholder="First name*").name
          input(type="text" placeholder="Last name*").name
        input(type="email" placeholder="Email*").email
        input(type="text" placeholder="Company").company
        input(type="text" placeholder="Leave a request we will write you").request
        a.send_btn Send message
</template>

<script>

export default {
  name: 'App',
  // components: {}
}
</script>

<style>
  * {
    padding: 0;
    margin: 0;
  }
  #app {
    display: flex;
    align-items: center;
    flex-direction: column;
  }
  .head_wrapper {
    display: flex;
    align-items: center;
    max-width: 1170px;
    width: 100%;
    justify-content: space-between;
  }
  .head_title {
    max-width: 786px;
    width: 100%;
    height: 134px;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 55px;
    line-height: 130%;
    text-transform: capitalize;
    color: #33484B;
  }
  .head_paragraph {
    max-width: 640px;
    width: 100%;
    height: 177px;
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 22px;
    line-height: 36px;
    color: #33484B;
    position: relative;
    margin-left: 100px;
    margin-top: 38px;
  }
  .head_paragraph:before {
    position: absolute;
    top: 24px;
    left: -100px;
    content: " ";
    width: 50px;
    border-top: solid 3px #334848;
  }
  .head_logo {
    margin-right: 30px;
  }

  .reasons_wrapper {
    display: flex;
    align-items: center;
    max-width: 1170px;
    width: 100%;
    flex-direction: column;
    background: #FFFFFF;
    box-shadow: 0px 0px 55px rgba(0, 0, 0, 0.05);
    border-radius: 20px;
    margin-top: 122px;
  }
  .reasons_title {
    height: 61px;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 45px;
    line-height: 150%;
    text-align: center;
    color: #33484B;
    margin-top: 50px;
  }
  .reasons_container {
    display: flex;
    width: 100%;
    flex-wrap: wrap;
    justify-content: center;
    padding-bottom: 60px;
  }
  .reason {
    max-width: 505px;
    width: 100%;
    padding: 40px;
  }
  .reasons_container .reason:nth-child(-n+2) {
    border-bottom: solid 1px #33484b2a;
  }
  .reason h3 {
    font-family: Catamaran;
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    line-height: 30px;
    text-transform: uppercase;
    color: #33484B;
  }
  .reason p {
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 33px;
    color: #33484B;
  }

  .specifics_wrapper {
    display: flex;
    width: 100%;
    background: #0080C7;
    justify-content: center;
    padding: 67px 0 23px 0;
  }
  .specifics_content {
    display: flex;
    max-width: 1170px;
    width: 100%;
  }
  .specifics_title {
    position: relative;
    width: 312px;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 40px;
    line-height: 150%;
    color: white;
    margin-right: 114px;
    height: 194px;
  }
  .specifics_title::after {
    position: absolute;
    left: 0;
    top: 100%;
    content: " ";
    width: 66px;
    border-top: solid 10px #FEBE41;
    margin-top: 15px;
  }
  .specifics_container {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
  }
  .specific {
    padding: 0 0 34px 60px;
  }
  .specific h3 {
    position: relative;
    max-width: 331px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 140%;
    color: #FFFFFF;
  }
  .specific h3::before {
    position: absolute;
    left: -25px;
    top: 25%;
    content: " ";
    width: 12px;
    border-top: solid 12px #FEBE41;
  }
  .specific p {
    max-width: 341px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 17px;
    line-height: 28px;
    color: #FFFFFF;
  }

  .industries_wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 1170px;
    width: 100%;
    margin-top: 82px;
  }
  .industries_title {
    max-width: 883px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 45px;
    line-height: 150%;
    text-align: center;
    color: #33484B;
  }
  .industries_container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  .industry {
    width: 344px;
    display: flex;
    margin-top: 50px;
  }
  .industry_img {
    margin-right: 24px;
  }
  .industry_text h3 {
    position: relative;
    font-family: Catamaran;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 33px;
    color: #33484B;
  }
  .industry_text p {
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 30px;
    color: #33484B;
  }

  .apps_wrapper {
    max-width: 1170px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 115px;
  }
  .apps_title {
    max-width: 724.37px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 45px;
    line-height: 150%;
    text-align: center;
    color: #33484B;
  }
  .apps_container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    width: 100%;
    margin-top: 40px;
  }
  .mobile_app {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .app_img {
    margin-bottom: 35px;
  }
  .app_text {
    max-width: 340px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-size: 18px;
    line-height: 130%;
    text-align: center;
    color: #33484B;
  }

  .offer_wrapper {
    display: flex;
    justify-content: center;
    background: #F3F7F8;
    width: 100%;
  }
  .offer_content {
    max-width: 1170px;
    width: 100%;
    display: flex;
    justify-content: center;
  }
  .offer_text_block {
    margin-top: 65px;
    margin-bottom: 65px;
  }
  .offer_title {
    max-width: 493px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 45px;
    line-height: 150%;
    color: #33484B;
  }
  .offer_paragraph {
    max-width: 637px;
    width: 100%;
    height: 119px;
    display: flex;
  }
  .offer_paragraph:hover {
    background-color: #fff;
    transition: 0.5s;
  }
  .offer_paragraph:hover h2 {
    color: #FEBE41;
    transition: 0.5s;
  }
  .offer_paragraph h2 {
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 50px;
    line-height: 160%;
    display: flex;
    align-items: center;
    color: #33484B;
    margin-left: 20px;
  }
  .offer_paragraph p {
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 160%;
    display: flex;
    align-items: center;
    color: #33484B;
    padding-left: 20px;
    padding-right: 55px;
  }
  .offer_img_block {
    max-width: 500px;
    width: 100%; 
  }
  .offer_img {
    position: absolute;
    max-width: 570px;
    width: 100%; 
    margin-top: 60px;
    left: 57%;
  }

  .why_choose_wrapper {
    margin-top: 160px;
    max-width: 900px;
    width: 100%;
    background: #FFFFFF;
    box-shadow: 0px 15px 55px rgba(0, 0, 0, 0.05);
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
  }
  .why_choose_wrapper::before {
    content: " ";
    background: #0080C7;
    width: 98.8vw;
    height: 212px;
    position: absolute;
    z-index: -1;
    top: -56px;
  }
  .why_choose_title {
    margin-top: 70px;
    max-width: 705px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 38px;
    line-height: 141%;
    text-align: center;
    color: #33484B;
  }
  .why_choose_text {
    margin-top: 10px;
    max-width: 778px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 26px;
    line-height: 43px;
    text-align: center;
    color: #33484B;
  }
  .why_choose_btn {
    margin: 36px 0 70px 0;
    display: block;
    color: white;
    max-width: 329.15px;
    width: 100%;
    height: 60px;
    background: linear-gradient(90deg, #FF7F24 0%, #FFAA37 100%);
    border-radius: 5px;
    font-family: Catamaran;
    font-style: normal;
    font-weight: bold;
    font-size: 22px;
    line-height: 36px;
    display: flex;
    align-items: center;
    text-align: center;
    padding-left: 40px;
  }
  .why_choose_btn span {
    font-size: 50px;
    padding-bottom: 12px;
  }

  .one_stop_shop_wrapper {
    max-width: 1170px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 85px;
  }
  .one_stop_shop_title {
    max-width: 673px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 50px;
    line-height: 150%;
    text-align: center;
    color: #33484B;
    margin-bottom: 37px;
  }
  .one_stop_shop_container {
    display: flex;
    width: 100%;
    justify-content: space-between;
  }
  .one_stop_shop_block {
    max-width: 536px;
    width: 100%;
    display: flex;
    align-items: flex-start;
  }
  .one_stop_shop_text {
    max-width: 420px;
    width: 100%;
    margin-left: 36px;
  }
  .one_stop_shop_text h3 {
    font-family: Catamaran;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 160%;
    color: #33484B;
  }
  .one_stop_shop_text p {
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 160%;
    color: #33484B;
  }

  .achievements_wrapper {
    margin-top: 89px;
    max-width: 425px;
    width: 100%;
  }
  .achievements_title {
    max-width: 425px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 40px;
    line-height: 150%;
    text-align: center;
    color: #33484B;
    margin-bottom: 48px;
  }
  .achievements_container {
    display: flex;
    width: 100%;
    justify-content: space-around;
  }

  .approach_wrapper {
    background: #F3F7F8;
    width: 100%;
    display: flex;
    justify-content: center;
    padding: 100px;
    transform: rotate(-4.63deg);
    margin-top: 80px;
  }
  .approach_content {
    display: flex;
    max-width: 1170px;
    width: 100%;
    align-items: center;
    justify-content: space-between;
    transform: rotate(4.63deg);
  }
  .approach_text {
    max-width: 487px;
    width: 100%;
  }
  .approach_text h2 {
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 55px;
    line-height: 150%;
    color: #33484B;
  }
  .approach_text p {
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 160%;
    color: #33484B;
  }
  .approach_content li {
    font-family: Catamaran;
    font-style: normal;
    font-weight: 500;
    font-size: 26px;
    line-height: 210%;
    display: flex;
    align-items: center;
    color: #33484B;
    position: relative;
  }
  .approach_content li::before {
    content: " ";
    position: absolute;
    height: 35px;
    width: 35px;
    background: #FFFFFF;
    border: 5px solid #FEBE41;
    box-sizing: border-box;
    border-radius: 50%;
    left: -62px;
  }
  .approach_content ul {
    position: relative;
  }
  .approach_content ul::before {
    content: " ";
    position: absolute;
    height: 350px;
    width: 1px;
    background: #33484B;
    left: -44.5px;
    top: 10px
  }

  .clients_wrapper {
    max-width: 1170px;
    width: 100%;
    margin-top: 80px;
  }
  .clients_title {
    font-family: Catamaran;
    font-style: normal;
    font-weight: 900;
    font-size: 50px;
    line-height: 82px;
    text-align: center;
    color: #33484B;
    margin-bottom: 45px;
  }
  .clients_container {
    display: flex;
    justify-content: space-between;
  }

  .join_wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 160px;
    max-width: 1170px;
    width: 100%;
  }
  .join_text {
    max-width: 525px;
    width: 100%;
  }
  .join_text h2 {
    max-width: 470px;
    width: 100%;
    font-family: Catamaran;
    font-style: normal;
    font-weight: 800;
    font-size: 40px;
    line-height: 150%;
    color: #33484B;
    margin-bottom: 35px;
  }
  .join_text p{
    font-family: Catamaran;
    font-style: normal;
    font-weight: normal;
    font-size: 26px;
    line-height: 43px;
    color: #33484B;
  }
  .join_form {
    display: flex;
    flex-direction: column;
    max-width: 534px;
    width: 100%;
  }
  .first_last_name {
    display: flex;
    justify-content: space-between;
  }
  .join_form input {
    margin-bottom: 25px;
    background: #FCFCFC;
    border: 1px solid #D7D7D7;
    box-sizing: border-box;
    border-radius: 5px;
    padding: 17px
  }
  .name {
    width: 255px;
  }
  .name, .email, .company, .request {
    height: 50px;
  }
  .request {
    height: 94px;
    padding: 0;
  }
  .send_btn {
    height: 60px;
    max-width: 533px;
    width: 100%;
    background: linear-gradient(90deg, #FF7F24 0%, #FFAA37 100%);
    border-radius: 5px;
    color: #FCFCFC;
    font-family: Catamaran;
    font-style: normal;
    font-weight: bold;
    font-size: 22px;
    line-height: 60px;
    display: flex;
    align-items: center;
    text-align: center;
    display: block;
  }
</style>
