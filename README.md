# TMGMT Express Checkout

Reduce amount of clicking when creating multiple translation jobs.

This adds an express checkout form that is automatically presented when 2 or more translation jobs need to be checked out. The form allows a single name and translator selection to be used for a set of jobs that translate the same documents into different languages.

The form can be skipped to proceed to the standard form-per-job checkout.


## Requirements

This module requires TMGMT module to be installed.


## Installation

Place the module directory in your usual Drupal modules directory.

Activate the module through the Drupal administration interface, or whichever
way you prefer to activate modules.


## Setup

After installing and activating the module, it should work with no additional
setup.


## Usage

Use TMGMT to create multiple translation jobs. For example add items to the
cart, open the cart and select multiple languages, then click "Request
translation".

The express checkout form will be shown automatically whenever multiple job
checkout forms would be shown.

To checkout all the jobs at once:

 - Enter a name to use for all the created jobs.
 - Select the translator plugin to use for all the created jobs.
 - Click "Request translation".

To skip express checkout and use the default checkout forms, click "Cancel
(resume normal checkout)".
