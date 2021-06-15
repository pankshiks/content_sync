
/******* PATCHES INFORMATION *********/

If getting issue with Content Sync module's or because of any other module, these patches can help for Content Sync module :

========
1. Module : classy_paragraphs

Issues :
    #1 issue : Route "entity.classy_paragraphs_style.canonical" does not exist. (../web/core/lib/Drupal/Core/Routing/RouteProvider.php:190)

    Solution link : https://www.drupal.org/project/classy_paragraphs/issues/2900726

    Working Patch : https://www.drupal.org/files/issues/2020-06-10/reroll-4-refactor_classy-2900726-9.patch

========
2. Module : content_sync

Issues :
    #1 issue : Import doesn't work; looking for entityManager on ContentEntityNormalizer

    Solution link : https://www.drupal.org/project/content_sync/issues/3052772

    Working Patch : https://www.drupal.org/files/issues/2019-05-06/content_sync-entity_manager_refs.patch


    #2 issue : The specified translation (und) cannot be removed

    Solution link : https://www.drupal.org/project/content_sync/issues/2973854

    Working Patch : https://www.drupal.org/files/issues/2018-05-18/2973854-1.patch
========


/******* PATCHES INFORMATION ENDS *********/


/******* COMPOSER INFORMATION *********/

If using composer, patches can be applied like this :

{
  "patches": {
    "drupal/MODULE MACHINE NAME": {    
       "ANY MESSAGE HERE": "PATCH LINK HERE"
    },
    "drupal/SECOND MODULE HERE": {
       "ANY MESSAGE HERE": "PATCH LINK HERE",
       "ANY MESSAGE HERE": "SECOND PATCH LINK HERE"
    }
  }
}

/******* COMPOSER INFORMATION ENDS *********/

