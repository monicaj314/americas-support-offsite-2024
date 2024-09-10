# Americas Support Offsite 2024

The goal of this session is for you to have a test site up and running with the Contentsquare, Heap, and Hotjar tags installed.

# Getting Started
- Fork this repo
- Name the repo <github_username>.github.io
- Make an edit to a file and save it to publish the site
- Check <github_username>.github.io to make sure you are able to view your site

# Hotjar
- Sign up for a [free trial](https://insights.hotjar.com/register)
- Docs
  - [How to Install your Hotjar Tracking Code](https://help.hotjar.com/hc/en-us/articles/115009336727-How-to-Install-Your-Hotjar-Tracking-Code)
    - Alternative Installation Methods
      - [Google Tag Manager](https://help.hotjar.com/hc/en-us/articles/115009499708-Install-the-Tracking-Code-with-Google-Tag-Manager)
      - [Adobe Tag Mangaer](https://help.hotjar.com/hc/en-us/articles/115012500187-Adobe-Dynamic-Tag-Manager)
      - [Segment](https://help.hotjar.com/hc/en-us/articles/115009347327-Using-Hotjar-with-Segment)
- Installation Verification
  - Developer Tools
    - Filter network requests for `hotjar`
  - [How to Check that Hotjar is Working](https://help.hotjar.com/hc/en-us/articles/360016303294-How-to-Check-That-Hotjar-Is-Working)
  - [Hotjar Debugger Extension](https://chromewebstore.google.com/detail/hotjar-support-chrome-ext/gjhpfpajjeajjhpdachbhgencpmjopke?pli=1)
    - [How to Install the New Hotjar Debugger](https://www.loom.com/share/554fecd8fda442f9b02aa769149eb09e)
    - [What does the Hotjar Debugger Do?](https://contentsquare.atlassian.net/wiki/spaces/SAL/pages/3656624312/Hotjar+Debugger+HJ+Sales)
# Contentsquare
- Use the following tag: `https://t.contentsquare.net/uxa/2c5142b15f133.js`
- Docs
  - [How to Install your CS Tracking Code](https://docs.contentsquare.com/en/web/)
  - [Custom HTML](https://docs.contentsquare.com/en/web/#custom-html)
    - Alternative Installation Methods
      - [Google Tag Manager](https://docs.contentsquare.com/en/web/#google-tag-manager-template)
      - [Adobe Tag Mangaer](https://docs.contentsquare.com/en/web/#adobe-launch)
- Installation Verification
  - Developer Tools
    - Check for the `CS_CONF` object in the console
    - Filter network request for `contentsquare`
  - [Download the CS Tracking Setup Assistant Extention](https://chromewebstore.google.com/detail/contentsquare-tracking-se/pfldcnnaiaiaogmpfdjjpdkpnigplfca?pli=1)
    - Check the configuration of the main tag, monitor all the pageviews, transactions, custom and dynamic variables sent to the Contentsquare servers
# Heap
- Sign up for a [free trial](https://heapanalytics.com/signup)
  - If you use your work email address, use plus addressing to create a unique email address
    - ex. `name+test_account@company.com`
- Docs
  - [How to Install your Heap Tracking Code](https://heapanalytics.com/app/install?showInstallFlowPage=true)
  - [Custom HTML](https://developers.heap.io/docs/web)
    - Alternative Installation Methods
      - [Google Tag Manager](https://developers.heap.io/docs/google-tag-manager)
      - [Segment](https://developers.heap.io/docs/segment-installation)
- Installation Verification
  - Developer Tools
    - Check for the `heap` object in the console
    - Filter network requests for `heap`
    - Use `heap.setLogLevel('trace')` to see information about the data that is captured and sent to Heap
  - [How to Check that Heap is Working](https://help.heap.io/getting-started/how-heap-works/how-can-i-check-if-heap-is-installed-correctly-on-my-website/)
  - [Live Data Feed](https://heapanalytics.com/app/live)
# Extra Credit
- Remove the tags from the site and install via [GTM[(https://tagmanager.google.com/#/home)
- Add [artificial pageviews](https://docs.contentsquare.com/en/web/artificial-pageviews) for Contentsquare
