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
    title: West Valley Radio
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
    type: HeroSection
    actions: []
    text: >+
      \<script type="text/javascript"
      src="https\://hosted.muses.org/mrp.js"></script>


      \<script type="text/javascript">

      MRP.insert({

      'url':'media.streambrothers.com/stream/8112',

      'lang':'en',

      'volume':100,

      'autoplay':false,

      'forceHTML5':true,

      'jsevents':true,

      'buffering':0,

      'title':'West Valley Radio',

      'wmode':'transparent',

      'skin':'cassette',

      'width':200,

      'height':120

      });

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
