---
draft: true
blocks:
  - style:
      alignment: 'flex-row-reverse text-left items-center sm:flex-col'
      featureContent: 'w-2/3 min-h-screen '
      padding: pt-11 pb-11 pr-0 pl-0
      featureImage: object-center object-scale-down to-edge
      imagePadding: pt-0 pb-0 pr-0 pl-0
      labelStyles: >-
        text-accent1 font-2 text-sm mb-0  sm:text-accent1 sm:font-2 sm:text-xs
        sm:mb-0 
      headlineStyles: >-
        text-accent1 font-1 text-2xl mb-14  sm:text-accent1 sm:font-1 sm:text-xl
        sm:mb-14 
      subheadStyles: 'text-accent1 font-2 text-lg mb-4 '
      textStyles: 'text-accent1 font-2 text-base mb-11 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-primary
      position: ''
    image:
      src: >-
        https://res.cloudinary.com/tombustout/image/upload/v1651547935/passport_img_uygam9.jpg
      alt: TRVL PASSPORT app shiny gold
    label: A NEW WORLD FOR TRAVELLERS
    headline: 'Build your travel identity, on-chain.'
    subhead: >-
      The TRVL Passport is filled with NFT stamps that represent your travel
      history, creating a unique system for reputation, credentials, and
      rewards.
    body: ''
    buttons:
      - label: Become a Passport Holder
        link: 'https://d2bpe117hv9.typeform.com/passportholder'
        type: solid
        buttonFillStyles: bg-accent1
        textColor: primary
        backgroundColor: ''
      - label: Become a Partner
        link: 'https://d2bpe117hv9.typeform.com/passportpartner'
        type: outline
        buttonFillStyles: bg-primary
        textColor: accent1
        backgroundColor: accent1
    _template: feature
  - style:
      minHeight: min-h-0
      fullWidth: false
      padding: pt-10 pb-10 pr-20 pl-20
    background:
      fillStyles: bg-black
      position: ''
    markup: |-
      <div id="background-video">
      <video autoplay playsinline>
        <source src="/passport-reveal.mp4" type='video/mp4;'>
      </video>
      </div>
      <style>
      @keyframes slideIn {
        from {
          display: none;
          transform: translateY(-100%);
          opacity: 0;
        }
        to {
          display: block;
          transform: translateY(0);
          opacity: 1;
        }
      }

        body { 
          background-color: #070706;
        }

        h1, h2, h3, h4, a {
          position:relative;
          z-index: 2;
        }

        a { 
          border-radius: 4px; 
          font-size: 18px !important; 
          line-height: 18px !important;
          height: unset !important;
          padding: 16px 24px; 
          transition: opacity .2s ease;
        }
        a:hover {
          opacity: .8;
        }
        [data-tinafield='blocks.1'] {
          background-color: #000000;
          position: absolute;
          top: 0;
          left: 0;
          height: 100vh;
          width: 100vw;
          z-index: 1;
        }
        #video-background {
          height: 100vh;
          overflow: hidden;
        }
        .max-w-desktop-full {
          max-width: 1400px;
        }
        [data-tinafield='blocks.1'] .max-w-desktop-full {
          max-width: 100vw !important; 
          padding: 0 !important;
        }

      h4 {  
        animation: 1.2s ease-out 0s 1 slideIn;
      }
      h1 {  
        animation: 1.3s ease-out 0s 1 slideIn;
      }
      h3 {  
        animation: 1.5s ease-out 0s 1 slideIn;
      }
      .order-4 {
        animation: 1.7s ease-out 0s 1 slideIn;
      }

      @media (min-width: 900px){
       [data-tinafield='blocks.1'] img {
          display: none;
        }
      }


      </style>
    navigationLabel: ''
    _template: embed
meta:
  pageTitle: TRVL PASSPORT
  pageDescription: 'Build your travel identity, on-chain.'
---

