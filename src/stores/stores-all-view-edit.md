---
title: Editing a Store View
---

Because the view name appears in the language chooser, you might eventually want to change the name of the default view to something more descriptive. The _Name_ field is simply a label, and can be easily changed.

If your Magento installation has a multisite or multi-store setup, do not change the store Code field without verifying that the value is not referenced in the `index.php` file. If you do not have access to the server to examine the file, ask a developer for help.

Field | Original value | Updated value
----- | -------------- | -------------
Name  | Default Store View | English
Code  | default | english
{:style="table-layout:auto"}

#### To edit a store view:

1.  On the _Admin_ sidebar, click **Stores**.

1.  Under _Settings_, choose **All Stores**.

1.  In the _Store View_ column of the grid, click the name of the view that you want to edit.

    When editing the default view, the Store and Status fields are not available.
   
    ![]({% link images/images/stores-all-edit-store-view-information.png %}){: .zoom}
    _Editing the Default View_

1.  Update the following fields as applicable:

    * Store (non-default views only)
    * Name
    * Code (only if not used in `index.php`)
    * Status (non-default views only)
    * Sort Order

1.  When complete, click **Save Store View**.

    ![]({% link images/images/stores-all-grid.png %}){: .zoom}
    _Stores_
