---
type: ProjectFeedLayout
title: PROJETOS
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/pexels-karolina-grabowska-6634136.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 50
projectFeed:
  type: ProjectFeedSection
  colors: colors-f
  showDate: false
  showDescription: true
  showReadMoreLink: true
  showFeaturedImage: true
  variant: variant-a
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: left
bottomSections:
  - type: ContactSection
    backgroundSize: full
    title: Alguma dúvida? Vamos conversar!
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: Nome
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
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
          width: full
          type: EmailFormControl
        - type: TextareaFormControl
          name: message
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
          - ml-4
          - mr-4
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
