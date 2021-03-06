# sliComments - Changelog #

## 1.3.2 / 2012-05-15 ##
  
  * Fix flagged filter not working.
  * Fix Strict Standards errors.
  * Redirect after change status of a comment.

## 1.3.1 / 2012-05-04 ##
  
  * Fixed pagination in the backend.

## 1.3.0 / 2012-03-25 ##

  * Added fr-FR translation. Thanks Anthony MOËLLO
  * Added es-ES translation. Thanks Emiliano Marini
  * Added flag system.
  * Added id to comments.
  * Added option to hide low-rated/flagged comments.
  * Added new event onAfterSaveComment.
  * Added Jomsocial plugin.
  * Added onVote event
  * Fixed: Template overrides not working for ajax requests.
  * Fixed: Guests were not able to rate comments.
  * Fixed: wrong filename for Dutch translation
  * Fixed: typo.
  * Check for request forgeries in the vote action.
  * Improved rating system.

## 1.2.2 / 2012-01-25 ##

  * Fixed XSS security issue.

## 1.2.1 / 2012-01-24 ##

  * Convert all the translation files to UTF-8 without BOM
  * Missing file for uk-UA translation

## 1.2.0 / 2012-01-24 ##

  * Add nl-NL translation. Thanks Jaco van Dieren
  * Add it-IT translation. Thanks Federico Ferrazzani
  * Add ru-RU translation. Thanks Алексей and Dmitry
  * Add uk-UA translation. Thanks Dmitry Krasnokutsky
  * Get avatar from third party components (Gravatar, Kunena, Jomsocial, K2)
  * Add option to display usernames instead of real names.
  * Some improvements in the layout.
  * Show a notice if the comment is pending approval.
  * Don't show comments links on categories that have comments disabled.

## 1.1.0 / 2012-01-11 ##

  * Top Comments.
  * Add comments count to the blog and featured views.
  * Show avatar next to the form if the user is logged in
  * Add pl-PL translation. Thanks Igor Czajka
  * Add de-DE translation. Thanks Jörg Fiedler
  * Small changes to the frontend layout

## 1.0.2 / 2012-01-05 ##

  * Fixed a issue with float on Firefox.
  * Use the translated messages in the form validator.
  * Add some default params.

## 1.0.1 / 2012-01-01 ##

  * Uncaught exception when voting on a comment and session has expired.
  * Fixed 2 untranslated strings.