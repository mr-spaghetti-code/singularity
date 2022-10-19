---
draft: true
blocks:
  - style:
      alignment: 'flex-row-reverse items-center items-center-vertical '
      padding: pt-48 pb-20 pr-20 pl-20
      featureImage: wpx-499 hpx- ml-auto
      featureContent: w-1/2 min-h-0 text-left
      labelStyles: text-white font-2 text-xl mb-0 font-bold
      headlineStyles: text-primary font-1 text-6xl mb-0 font-bold
      subheadStyles: text-gray font-1 text-xl mb-7 font-bold
      textStyles: 'text-white font-1 text-lg mb-11 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: from-accent1 to-black bg-gradient-to-br opacity-100
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1649882497/microgen/Hall_of_Fame_grccee_k39etu.png
      alt: Illustration of space shuttles
    label: ''
    headline: Singularity
    subhead: A new tool for data onboarding on Filecoin
    body: >
      Make [modern web 3.0](#) ready websites with a real-time visual editor. An
      edit.
    buttons:
      - label: Get Started
        link: 'https://github.com/pathfindertools/microgen'
        type: primary
    _template: feature
  - style:
      minHeight: min-h-0
      fullWidth: true
      padding: pt-20 pr-10 pb-20 pl-10
    background:
      fillStyles: from-black to-accent1 bg-gradient-to-bl opacity-100
    markup: |-

      <div id="default-carousel" class="relative" data-carousel="static">
          <!-- Carousel wrapper -->
          <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
               <!-- Item 1 -->
              <div class="duration-700 ease-in-out absolute inset-0 transition-all transform translate-x-0 z-20" data-carousel-item="">
                  <span class="absolute text-2xl font-semibold text-white -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2 sm:text-3xl dark:text-gray-800">First Slide</span>
                  <img src="/docs/images/carousel/carousel-1.svg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
              </div>
              <!-- Item 2 -->
              <div class="duration-700 ease-in-out absolute inset-0 transition-all transform translate-x-full z-10" data-carousel-item="">
                  <img src="/docs/images/carousel/carousel-2.svg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
              </div>
              <!-- Item 3 -->
              <div class="duration-700 ease-in-out absolute inset-0 transition-all transform -translate-x-full z-10" data-carousel-item="">
                  <img src="/docs/images/carousel/carousel-3.svg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
              </div>
          </div>
          <!-- Slider indicators -->
          <div class="absolute z-30 flex space-x-3 -translate-x-1/2 bottom-5 left-1/2">
              <button type="button" class="w-3 h-3 rounded-full bg-white dark:bg-gray-800" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0"></button>
              <button type="button" class="w-3 h-3 rounded-full bg-white/50 dark:bg-gray-800/50 hover:bg-white dark:hover:bg-gray-800" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
              <button type="button" class="w-3 h-3 rounded-full bg-white/50 dark:bg-gray-800/50 hover:bg-white dark:hover:bg-gray-800" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
          </div>
          <!-- Slider controls -->
          <button type="button" class="absolute top-0 left-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-prev="">
              <span class="inline-flex items-center justify-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                  <svg aria-hidden="true" class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"></path></svg>
                  <span class="sr-only">Previous</span>
              </span>
          </button>
          <button type="button" class="absolute top-0 right-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-next="">
              <span class="inline-flex items-center justify-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                  <svg aria-hidden="true" class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                  <span class="sr-only">Next</span>
              </span>
          </button>
      </div>
    _template: embed
  - style:
      textAlignment: text-left
      minHeight: min-h-0
      padding: pt-20 pb-20 pr-20 pl-20
      contentWidth: w-full
      columns: '2'
      labelStyles: text-black font-1 text-xl mb-0 font-bold
      headlineStyles: text-white undefined text-5xl mb-11 font-bold
      subheadStyles: text-black undefined text-3xl mb-0 font-bold
      textStyles: text-black undefined text-lg mb-0 font-bold
      contentOrder: labelHeadingsContent
    cardStyle:
      fillStyles: bg-accent1 opacity-100
      padding: pt-4 pb-4 pr-5 pl-7
      borderStyles: border-primary border-3
      labelStyles: 'text-black undefined text-sm mb-0 '
      headlineStyles: text-primary font-1 text-xl mb-2 font-bold
      subheadStyles: 'text-black undefined text-lg mb-0 '
      textStyles: 'text-gray-light undefined text-lg mb-0 '
      buttonType: primary
    background:
      fillStyles: from-black to-accent1 bg-gradient-to-bl opacity-100
    label: ''
    headline: Features
    subhead: ''
    body: ''
    items:
      - headline: Deploy Quickly
        subhead: ''
        text: >
          Get a website complete with a visual CMS deployed in less than an hour
          on your choice of static host.
        link: ye
        buttonLabel: ''
      - headline: Modern Features
        subhead: ''
        text: >
          Responsive design, open graph social sharing and google analytics on
          every site.
      - headline: Custom Design
        subhead: ''
        text: >
          Customize the look and feel of your site with a realtime visual
          editor, without writing a single line of code.
      - headline: Git Based
        subhead: ''
        text: |
          Version controlled content and design.
    navigationLabel: Features
    _template: textCards
  - style:
      textAlignment: text-center
      minHeight: min-h-0
      padding: pt-7 pb-10 pr-0 undefined
      width: normal
      labelStyles: text-black undefined text-xl mb-0 font-bold
      headlineStyles: text-white undefined text-6xl mb-3 font-bold
      subheadStyles: text-black undefined text-3xl mb-0 font-bold
      textStyles: text-black undefined text-lg mb-0 font-bold
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-primary
    label: ''
    headline: Learn More
    subhead: ''
    body: ''
    buttons:
      - label: Get Started
        link: 'https://github.com/filecoin-project/microgen'
        type: secondary
    _template: banner
  - style:
      minHeight: min-h-0
      fullWidth: false
      padding: pt-10 pb-10 pr-20 pl-20
    background:
      fillStyles: bg-black
    markup: <p class="text-white">I am an embed</p>
    navigationLabel: Embed
    _template: embed
  - style:
      textAlignment: text-left
      minHeight: min-h-0
      padding: pt-14 pb-20 pr-20 pl-20
      contentWidth: w-full
      columns: '2'
      labelStyles: text-black undefined text-xl mb-0 font-bold
      headlineStyles: text-white undefined text-6xl mb-10 font-bold
      subheadStyles: text-black undefined text-3xl mb-0 font-bold
      textStyles: text-black undefined text-lg mb-0 font-bold
      contentOrder: labelHeadingsContent
    cardStyle:
      fillStyles: bg-primary opacity-100
      padding: pt-5 pb-5 pr-5 pl-5
      borderStyles: border-white border-0
      imageStyles: ' undefined undefined mb-0'
      labelStyles: 'text-white undefined text-sm mb-0 '
      headlineStyles: 'text-white undefined text-2xl mb-0 '
      subheadStyles: 'text-white undefined text-lg mb-0 '
      textStyles: 'text-white undefined undefined mb-0 '
      buttonType: secondary
    background:
      fillStyles: bg-accent1
    label: ''
    headline: Made with Microgen
    subhead: ''
    body: ''
    items:
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799687/microgen/sustainable-blockchain_dqbwkm.jpg
        headline: Sustainable Blockchain Summit
        text: >
          Two days of talks, workshops and discussions on how we can work
          together to develop and build greener blockchain solutions.
        link: 'https://sbs.tech/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799682/microgen/consensus-factory_g7ol2z.jpg
        headline: 'Consensus Factory '
        text: >
          Consensus is at the heart of decentralised systems, having taken
          centre stage with the introduction of Nakamoto’s Proof-of-Work (PoW)
          algorithm.
        link: 'https://consensus-factory.io/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799690/microgen/vector-commitment_i0nrao.jpg
        headline: Vector Commitment Day
        text: >
          Vector commitments are powerful primitives that find applications in
          many blockchains protocols. The goal of this workshop is to survey the
          state of the art in research.
        link: 'https://cryptonet.vercel.app/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799685/microgen/large-data_ulkv86.jpg
        headline: Filecoin Large Data
        subhead: ''
        text: "[Filecoin](https://filecoin.io/)\_is an open Web3 alternative to cloud storage, with better interoperability and larger capacity at a lower cost.\n"
        link: 'https://largedata.filecoin.io/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1649882496/microgen/hackathons_z7pwah_ulntqb.png
        headline: Hackathons
        subhead: ''
        text: >
          With Filecoin and IPFS, we empower developers and entrepreneurs to
          solve significant problems and ship innovative applications.
        link: 'https://hackathons.filecoin.io/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1649882497/microgen/asia-season_sn2gv8_bj7ovk.png
        headline: Asia Hackathon Season
        subhead: ''
        text: >
          Join us on a journey across the universe of Filecoin and IPFS across
          four distinct hackathon events.
        link: 'https://hackathons.filecoin.io/asia-hackathon-season.html'
        buttonLabel: Visit Site
    navigationLabel: Made with Microgen
    _template: photoCards
meta:
  pageTitle: Singularity
  pageDescription: Make modern web 3.0 ready websites with a real-time visual editor.
---

