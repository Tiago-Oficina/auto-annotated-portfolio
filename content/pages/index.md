---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/pexels-karolina-grabowska-6634136.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: TIAGO RIBEIRO
    subtitle: PROGRAMADOR
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    media:
      type: ImageBlock
      url: /images/VIT_2976.JPG
      altText: Tiago
      caption: ''
      elementId: ''
    text: >
      ***SOBRE MIM!***


      Olá! Chamo-me Tiago Ribeiro, tenho 17 anos e sou aluno no curso de Gestão
      e Programação de Sistemas Informáticos na OFICINA - Escola Profissional!
      Gosto de ajudar os outros, trabalhar em equipa e manter a união. Nos meus
      tempos gosto de estar com a minha família, ouvir música, jogar futebol e
      videojogos.
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
        justifyContent: center
        borderWidth: 1
  - colors: colors-b
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
        borderStyle: solid
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: 'PROJETOS REALIZADOS '
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-36
          - pb-36
        justifyContent: center
        borderWidth: 1
  - type: FeaturedItemsSection
    title: ALGUMAS LINGUAGENS APRENDIDAS
    items:
      - type: FeaturedItem
        title: PYTHON
        subtitle: ''
        text: |+


        featuredImage:
          type: ImageBlock
          url: /images/pn.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: JAVA
        subtitle: ''
        text: ''
        featuredImage:
          type: ImageBlock
          url: /images/jn.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: PHP
        subtitle: ''
        text: ''
        featuredImage:
          type: ImageBlock
          url: /images/phn.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-b
    columns: 1
    spacingX: 16
    spacingY: 16
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
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
        justifyContent: center
        borderWidth: 1
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Tem alguma pergunta? Contacte-me
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: Nome
          label: Nome
          hideLabel: true
          placeholder: Nome
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: Apelido
          label: 'Apelido '
          hideLabel: true
          placeholder: Apelido
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
        - type: TextareaFormControl
          name: Mensagem
          label: Mensagem
          hideLabel: false
          placeholder: Escreva aqui a sua mensagem
          width: full
          isRequired: false
        - name: updatesConsent
          label: Inscrever me para receber atualizações
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submeter✅
      styles:
        submitLabel:
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
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
