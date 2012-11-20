.. _templatetags:


Template Tags
=============

There are three inclusion tags to make it easy to put various forms
within your templates.

change_plan_form
----------------

:template: payments/_change_plan_form.html
:context: `form`, which is an instance of the `payments.forms.ChangePlanForm`


change_card_form
----------------

:template: payments/_change_plan_form.html
:context: `form`, which is an instance of the `payments.forms.CardTokenForm`



subscribe_form
--------------

:template: payments/_subscribe_form.html
:context: `form`, which is an instance of the `payments.forms.SubscribeForm`; `plans`, which is the `settings.PAYMENTS_PLANS` dictionary

