---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/featured-Image2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: ''
    subtitle: ''
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: center
        borderColor: border-(--theme-light)
        borderWidth: 0
        borderStyle: double
        borderRadius: none
    type: HeroSection
    actions: []
    text: >+
      <h1 style="font-size: 2.5rem; font-weight: bold; text-align: center;">
        <span style="background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet); 
                     -webkit-background-clip: text;
                     -webkit-text-fill-color: transparent;
                     display: inline-block;">
          West Valley Radio
        </span>
      </h1>


      <div style="max-width: 400px; margin: 20px auto; border-radius: 12px;
      overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
        <iframe src="https://media.streambrothers.com/AudioPlayer/8112?mount=stream" width="100%" height="120" style="border: 0;"></iframe>
      </div>




      \<script type="text/javascript">

      var Tawk\_API=Tawk\_API||{}, Tawk\_LoadStart=new Date();

      (function(){

      var
      s1=document.createElement("script"),s0=document.getElementsByTagName("script")\[0];

      s1.async=true;

      s1.src='https://embed.tawk.to/685108bc0fc35c191744afa7/1itu8k8c9';

      s1.charset='UTF-8';

      s1.setAttribute('crossorigin','\*');

      s0.parentNode.insertBefore(s1,s0);

      })();

      </script>



  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: narrow
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        borderWidth: 1
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Contact Us
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: 'Submit '
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
