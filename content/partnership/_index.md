---
title: Stratégie de numérisation
type: form
build:
  list: never
description: |-
  La numérisation a des impacts sur les modes de vies, les modes de productions, notre droit,... les milieux naturelles.

  Nos modes d'organisation, des décisions, de suivi de l'assurance qualité... sont-ils adaptés pour que la numérisation soit au service l'expression citoyenne&nbsp;?
  
  Quels seraient les facteurs de succès&nbsp;?

form:
  - title: Pour commencer, parlez-nous de vous
    questions:
      - label: Votre Nom
        name: name
        type: text
        placeholder: Prénom Nom
        help: "(Vous pouvez répondre de manière anonyme : ne rien mettre dans ce champs)"
      - label: Votre secteur d'activité, si applicable
        name: sector
        type: text
        placeholder: Nom du secteur
        help: "(Donnez le nom du secteur)"
      - label: Quel type de travail pratiquez vous&nbsp;?
        name: jobtitle
        type: text
        placeholder: Nom de la fonction
      - label: Vos pays d'activité
        name: countries
        type: text
        placeholder: Ouganda, Niger, Mali
        help: "(Inscrivez des noms de pays séparés par des virgules)"
      - label: Quel est, selon vous, votre niveau de maîtrise des outils numériques&nbsp;?
        name: estimated-knowledge-digital
        type: radio
        help: (Ex. Vous savez corriger une ligne de code, vous savez comment fonctionne un data center, vois savez réinstaller un système d'exploitation sur un pépriphérique...)
        element:
          - label: aucune
          - label: réduite
          - label: moyenne
          - label: importante
          - label: majeure
      - label: Quel est, selon vous, votre niveau de connaissance concernant l'accessibilité numérique&nbsp;?
        name: estimated-knowledge-accessibility
        type: radio
        help: (Ex. Prise en compte des différents handicaps dans vos activités, connaissance des lois qui s'appliquent dans votre contexte, impacts sur les bénéficiaires...)
        element:
          - label: aucune
          - label: réduite
          - label: moyenne
          - label: importante
          - label: majeure
  - title: Faire partie d'une liste partenaire Handicap Internationale pour ses missions sur le numérique
    questions:
      - label: Seriez vous intéressez pour être partenaire ?
        name: partner
        type: radio
        element:
          - label: Oui
          - label: Non
        help: (Consultance, partenariat sur des missions, expertise sur le terrain...)
      - label: Votre adresse mail
        name: email
        type: email
        placeholder: georges.dupont@mail.com
        help: "(Adresse stockée uniquement par l'équipe Social & Inclusion pour nos échanges)"
---
