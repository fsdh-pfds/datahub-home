---
title: "Sécurité"
date: 2025-02-17
draft: false
sidebar: false
showToc: false
translationKey: "security"
---

La Plateforme fédérale de données scientifiques (PFDS) est hébergée dans Azure Entreprise Cloud. La solution Azure Entreprise est conçue spécifiquement pour une utilisation au sein du gouvernement du Canada et est conçue pour répondre aux besoins de gestion centrale des identités et des accès, de gouvernance, de sécurité des données, de journalisation complète et de conception/segmentation de réseau selon les spécifications ITSG-33 du Centre canadien pour la cybersécurité. 

## La Plateforme fédérale de données scientifiques (PFDS) pratique la sécurité continue 

Nous intégrons des spécialistes de la sécurité à notre équipe et traitons les priorités en matière de sécurité comme des contraintes de conception. Nous utilisons l'automatisation et des mesures pour faciliter les opérations de sécurité.  

Conscients du rôle de la communication dans le maintien de la sécurité, nous : 

- Simplifions le langage afin que le personnel non spécialisé puisse participer. 
- Vous demandons de lire nos conditions générales lors de votre inscription. Vous devez également accepter les conditions générales chaque fois que vous vous connectez. 
- Réduisons la paperasse pour nous concentrer sur les documents utiles et spécifiques. 

Nous utilisons une combinaison précise de politiques, de pratiques et de produits de sécurité pour la PFDS. Cette combinaison est appelée contrôles de sécurité. 

Pour identifier ces contrôles, nous avons tenu compte des besoins de la PFDS en matière de : 

- **Confidentialité** - Empêcher l'accès non autorisé aux informations. 
- **Intégrité** - Empêcher la modification ou la suppression d'informations. 
- **Disponibilité** – Maintien des opérations lors d'événements tels que des pannes de courant ou des catastrophes naturelles.  

Le profil de sécurité de la PFDS a été élaboré et évalué par un évaluateur de sécurité indépendant en fonction de ces besoins. L'exigence de sécurité pour l'application PFDS est le niveau de sécurité « non classifié, confidentialité, faible intégrité, faible disponibilité » (NCC-FID) (lien) et est conçu pour se conformer aux contrôles de sécurité tels que les contrôles de sécurité technique, les contrôles de sécurité opérationnelle et les contrôles de sécurité de gestion selon les spécifications ITSG-33 du Centre canadien pour la cybersécurité. NCC-FID est un profil de sécurité pour le gouvernement du Canada.  

Grâce à l'utilisation de ces contrôles et d'autres mesures de protection, le risque résiduel lié à l'exploitation de la PFDS est acceptable. En 2025, le Bureau de la gestion et de la gouvernance de la sécurité de SPC a accordé à la PFDS l'autorisation d'exploitation (ATO). 

## Utilisation de la PFDS pour les données et informations non classifiées 

Lorsque vous utilisez un espace de travail PFDS et les outils qu'il contient, votre organisation est responsable de : 

- Évaluer le contexte pour décider du degré de préjudice pouvant résulter de la divulgation d'informations, et 
- Sur la base de votre évaluation, décider du niveau de sécurité suffisant. Si Non classifié ou inférieur n'est pas suffisant, n'utilisez pas la PFDS. 
La mise à disposition d'une solution plus sécurisée vous permettant d'héberger des classifications de données jusqu'à Protégé B est prévue et devrait être livrée au quatrième trimestre de l'exercice 2025/26. 

## Nous conservons les informations personnelles pendant toute la durée de l'espace de travail PFDS 

Les informations personnelles recueillies pour la création et le fonctionnement d'un espace de travail PFDS seront conservées pendant toute la durée de l'espace de travail. Après la suppression d'un espace de travail, seules les données non identifiantes seront conservées à des fins statistiques. 

Nous éliminons également les informations personnelles conformément à l'Annexe E : Norme sur la confidentialité dans l'analyse Web de la Directive sur les pratiques de confidentialité. Nous ne transmettons jamais les informations à un autre fournisseur de services, qu'il soit public ou privé. Pour plus d'informations, lisez la <gcds-link href="/a-propos/confidentialite" variant="light" class="hydrated">déclaration de confidentialité de la PFDS</gcds-link>. 

## Nous contrôlons l'accès aux informations dans la PFDS 

La PFDS contrôle l'accès aux informations dans le cloud. Nous empêchons et détectons les accès non autorisés à l'aide de pratiques automatisées appelées garde-fous.  

Nous limitons l'accès de notre personnel aux informations en fonction de son rôle et contrôlons régulièrement les accès et les autorisations. Nous incluons des mesures de protection pour l'intégration et la sortie du personnel de la PFDS. 

Nous surveillons également la PFDS pour enregistrer l'activité et recevoir des alertes sur tout ce qui est suspect. 

## Nous prenons des mesures pour protéger votre compte 

Lorsque vous vous connectez, nous envoyons un code à usage unique à votre adresse électronique ou à votre téléphone. Vous devrez entrer le code pour terminer la connexion. 

Nous utilisons un processus appelé hachage pour stocker et vérifier votre mot de passe en toute sécurité. Le hachage garantit que les mots de passe ne peuvent pas être déchiffrés ou reconstruits, même par le personnel de la PFDS. Si vous oubliez ou perdez votre mot de passe, vous devrez en créer un nouveau. 

Si nous soupçonnons qu'un compte ou un espace de travail est compromis, nous lancerons immédiatement le processus de gestion des incidents et des événements de sécurité du SSC. Cela peut inclure la désactivation des comptes et l'isolement des ressources de la PFDS. 

## Nous prévenons, détectons, traitons et minimisons les risques 

Le cloud d'entreprise a mis en place une architecture avec une surveillance centralisée de tous les journaux d'audit créés au sein du cloud d'entreprise. Le groupe de ressources utilise le service Azure Monitor pour collecter les journaux de sécurité de la plateforme. Azure Monitor est un service de surveillance complet fourni par Microsoft Azure qui vous aide à maximiser les performances et la disponibilité de vos applications et des ressources d'infrastructure exécutées dans Azure. Il collecte des données de télémétrie provenant de diverses sources, analyse ces données pour fournir des informations et vous permet de prendre des mesures proactives pour optimiser les performances, identifier les problèmes de sécurité et résoudre efficacement les problèmes.  

Le service de surveillance du réseau est également utilisé dans la solution de la plateforme PFDS. Il fournit un ensemble d'outils et de fonctionnalités qui nous aident à surveiller et à résoudre les problèmes de connectivité réseau, de sécurité et de performance.  

Du côté des applications, la plateforme utilise le service Azure Application Insights comme service de surveillance des performances des applications (APM) et d'analyse des applications. Il vous permet de surveiller et d'obtenir des informations sur les performances et l'utilisation de vos applications en temps réel.  

Les développeurs effectuent des tests manuels pour s'assurer que le système fonctionne correctement et en toute sécurité. Cette approche pratique consiste à examiner systématiquement les caractéristiques, les fonctionnalités et les mesures de sécurité du système afin d'identifier et de résoudre tout problème potentiel. En testant manuellement le système, les développeurs peuvent valider son comportement dans divers scénarios, vérifier qu'il répond aux exigences fonctionnelles, et détecter et atténuer les vulnérabilités de sécurité. Le plan dans les étapes ultérieures est d'automatiser ces tests et d'éviter les tests manuels.  

Une analyse de vulnérabilité est effectuée chaque année pour s'assurer que le système reste sécurisé. 

## Si vous soupçonnez une faille de sécurité ou si vous découvrez une vulnérabilité 

Les incidents doivent être signalés par téléphone au ESD via le numéro gratuit 1-855-830-7782. Le BSE offre un soutien 24 heures sur 24, 7 jours sur 7. Pour déterminer la gravité de l'incident (élevée, critique), consultez la matrice de priorité du SSC (Annexes B, C et D - Matrice de priorité du SSC).  

Les renseignements minimaux requis pour ouvrir un billet se trouvent sur le site GCPedia du BSE, Bureau de services partagés Canada, Demande de service et modèle d'incident du Bureau de services partagés. (Téléchargement MS Word)  

Des renseignements supplémentaires sur les processus du BPE sont disponibles sur le site GCpédia du BPE, Bureau de services partagés. 

FAQ https://www.gcpedia.gc.ca/wiki/SSC_IM_FAQ 

## Vous avez des responsabilités en matière de sécurité 

Conformément aux conditions générales de la PFDS, vous avez les responsabilités suivantes en matière de sécurité : 

- Utiliser un navigateur Web moderne et sécurisé.  
- Effectuer une analyse antivirus des données ou des fichiers d'information avant de les télécharger dans l'espace de travail. Si un fichier infecté est détecté, il ne doit pas être téléchargé. 
- Connaître les directives de sécurité informatique pour la gestion et la protection des mots de passe et accepter les conditions générales 
- S'assurer que les jetons d'accès liés au stockage sont gérés de manière sécurisée. En cas de question, contacter l'équipe de sécurité de votre département pour obtenir des conseils.  
- Vérifier que l'équipe de sécurité du département a élaboré et documenté :  
   - Une politique de réponse aux incidents qui traite de l'objectif, de la portée, des rôles, des responsabilités, de l'engagement de la direction, de la coordination entre les entités organisationnelles et de la conformité ; et  
   - Des procédures pour faciliter la mise en œuvre de la politique de réponse aux incidents et des contrôles associés.  
- Signaler les incidents à l'équipe de sécurité du département dès qu'ils se produisent et en suivant le processus de signalement des incidents du département.  
- Veiller à ce que tous les utilisateurs d'un espace de travail suivent une formation de sensibilisation à la sécurité, en particulier les cours suivants :  
   - Sensibilisation à la sécurité (COR310) 
   - Découvrir la cybersécurité (DDN235) 
   - Principes fondamentaux de l'accès à l'information et de la protection de la vie privée (COR502)  
- Gérer les identifiants de base de données. Les identifiants de base de données sont cryptés en transit et au repos et doivent être protégés. 