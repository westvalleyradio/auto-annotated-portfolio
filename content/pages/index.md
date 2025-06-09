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
    text: "<!DOCTYPE html><html lang=\"en\"><head><meta charset=\"UTF-8\" /><meta name=\"viewport\" content=\"width=device-width, initial-scale=1, maximum-scale=1\" /><title>West Valley Radio Player</title>\n<style>\_\_body {\_\_\_\_margin: 0;\_\_\_\_padding: 0;\_\_\_\_background-color: #999999;\_\_}</style>\n<link href=\"audio9\\_html5.css\" rel=\"stylesheet\" type=\"text/css\" /><link href=\"https\\://fonts.googleapis.com/css?family=PT+Sans:400,400i,700,700i\" rel=\"stylesheet\" />\n\\<script src=\"https\\://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js\"></script>\\<script src=\"https\\://ajax.googleapis.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js\"></script>\\<script src=\"js/jquery.mousewheel.min.js\" type=\"text/javascript\"></script>\\<script src=\"js/jquery.touchSwipe.min.js\" type=\"text/javascript\"></script>\\<script src=\"js/audio9\\_html5.js\" type=\"text/javascript\"></script></head>\n<body>\_\_<div id=\"lbg\\_audio9\\_html5\\_radio\\_zuper\\_1\"></div>\n\_\_\\<script>\_\_\_\_jQuery(function () {\_\_\_\_\_\_setTimeout(function () {\_\_\_\_\_\_\_\_jQuery(\"#lbg\\_audio9\\_html5\\_radio\\_zuper\\_1\").audio9\\_html5({\_\_\_\_\_\_\_\_\_\_radio\\_stream: \"https\\://media.streambrothers.com/stream/8112\",\_\_\_\_\_\_\_\_\_\_url\\_custom\\_metdata\\_file: '',\_\_\_\_\_\_\_\_\_\_metadata\\_file\\_type: '',\_\_\_\_\_\_\_\_\_\_radio\\_name: \"West Valley Radio\",\_\_\_\_\_\_\_\_\_\_playerWidth: 355,\_\_\_\_\_\_\_\_\_\_imageHeight: 355,\_\_\_\_\_\_\_\_\_\_skin: \"blackControllers\",\_\_\_\_\_\_\_\_\_\_responsive: true,\_\_\_\_\_\_\_\_\_\_grabLastFmPhoto: true,\_\_\_\_\_\_\_\_\_\_autoPlay: false,\_\_\_\_\_\_\_\_\_\_songTitleColor: \"#ffffff\",\_\_\_\_\_\_\_\_\_\_authorTitleColor: \"#ffffff\",\_\_\_\_\_\_\_\_\_\_lineSeparatorColor: \"#ffffff\",\_\_\_\_\_\_\_\_\_\_lineSeparatorOpacity: 50,\_\_\_\_\_\_\_\_\_\_radioStationColor: \"#ffffff\",\_\_\_\_\_\_\_\_\_\_frameBehindTextColor: \"controllers/minimalBGD1.jpg\",\_\_\_\_\_\_\_\_\_\_buttonsOffState: \"#ffffff\",\_\_\_\_\_\_\_\_\_\_buttonsOnState: \"#00a6e7\",\_\_\_\_\_\_\_\_\_\_sticky: false,\_\_\_\_\_\_\_\_\_\_startMinified: false,\_\_\_\_\_\_\_\_\_\_centerPlayer: true,\_\_\_\_\_\_\_\_\_\_centerTitle: true,\_\_\_\_\_\_\_\_\_\_playerBorderSize: 0,\_\_\_\_\_\_\_\_\_\_playerBorderColor: \"#000000\",\_\_\_\_\_\_\_\_\_\_showFacebookBut: true,\_\_\_\_\_\_\_\_\_\_facebookAppID: \"132026667482795\",\_\_\_\_\_\_\_\_\_\_facebookShareTitle: \"West Valley Radio\",\_\_\_\_\_\_\_\_\_\_facebookShareDescription: \"Streaming the best music around Phoenix and beyond!\",\_\_\_\_\_\_\_\_\_\_facebookShareImage: \"\",\_\_\_\_\_\_\_\_\_\_showTwitterBut: true,\_\_\_\_\_\_\_\_\_\_showVolume: true,\_\_\_\_\_\_\_\_\_\_showBioBut: true,\_\_\_\_\_\_\_\_\_\_translateBio: \"Bio\",\_\_\_\_\_\_\_\_\_\_bioAndLyricsColor: \"#000000\",\_\_\_\_\_\_\_\_\_\_showRadioStation: true,\_\_\_\_\_\_\_\_\_\_showTitle: true,\_\_\_\_\_\_\_\_\_\_showHistoryBut: true,\_\_\_\_\_\_\_\_\_\_translateReadingData: \"reading data...\",\_\_\_\_\_\_\_\_\_\_historyTranslate: \"HISTORY - latest played songs\",\_\_\_\_\_\_\_\_\_\_historyTitleColor: \"#00a6e7\",\_\_\_\_\_\_\_\_\_\_historyBgColor: \"#f5f5f5\",\_\_\_\_\_\_\_\_\_\_historyBgColorAlpha: 0.9,\_\_\_\_\_\_\_\_\_\_historyRecordBgColor: \"transparent\",\_\_\_\_\_\_\_\_\_\_historyRecordBottomBorderColor: \"transparent\",\_\_\_\_\_\_\_\_\_\_historyRecordSongColor: \"#000000\",\_\_\_\_\_\_\_\_\_\_historyRecordSongBottomBorderColor: \"#00a6e7\",\_\_\_\_\_\_\_\_\_\_historyRecordAuthorColor: \"#6d6d6d\",\_\_\_\_\_\_\_\_\_\_historyRecordThumbBorderColor: \"#00a6e7\",\_\_\_\_\_\_\_\_\_\_numberOfThumbsPerScreen: 3,\_\_\_\_\_\_\_\_\_\_historyPadding: 16,\_\_\_\_\_\_\_\_\_\_historyRecordTitleLimit: 25,\_\_\_\_\_\_\_\_\_\_historyRecordAuthorLimit: 36,\_\_\_\_\_\_\_\_\_\_nowPlayingInterval: 40,\_\_\_\_\_\_\_\_\_\_noImageAvailable: \"noimageavailable.jpg\",\_\_\_\_\_\_\_\_\_\_textureOverImage: \"controllers/texture4x4\\_1.png\"\_\_\_\_\_\_\_\_});\_\_\_\_\_\_}, 1000);\_\_\_\_});\_\_</script></body></html>\n"
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
