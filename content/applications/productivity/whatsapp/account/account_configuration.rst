======================================
Add WhatsApp Bussiness Account in Odoo
======================================

To add your :doc:`WhatsApp Bussiness Account  <account_create_on_meta>` To Odoo database
Go to :menuselection:`Whatsapp --> Configuration --> Accounts`. Here you can simply add
your whatsapp account by clicking on :guilabel:`NEW` adding credentials such as phone
number ID and access token.

Fill out the details about your :doc:`WhatsApp Bussiness Account  <account_create_on_meta>`.

.. image:: account_configuration/wapp-account-form.png
   :align: center
   :alt: Set The values for New Whatsapp Account creation

- :guilabel:`Name`: User can give any convenient name to WhatsApp Account. It will be helpful for user
  to identify in case of multiple :doc:`WhatsApp Bussiness Account  <account_create_on_meta>`.
- :guilabel:`Phone Number Id`: Here user needs to provide Phone number id for
  :doc:`WhatsApp Bussiness Account  <account_create_on_meta>` which User would have got at the time of creating
  the :doc:`WhatsApp Bussiness Account  <account_create_on_meta>`.
- :guilabel:`Access Token`: User needs to enter access token from the :guilabel:`Meta
  Whatsapp API`.
- :guilabel:`Webhook Verify Token`: You can enter any token. This will be required while
  verifying Webhook on the :guilabel:`Meta Whatsapp API`.
- :guilabel:`Callback URL`: It will be the URL where :guilabel:`Meta Whatsapp API` will
  send the callback when WhatsApp user replies to the Bussiness.
- :guilabel:`WhatsApp Business Account ID`: User needs to enter the business account id from the
  :guilabel:`Meta Whatsapp API` credentials.
- :guilabel:`App ID`: App Id will be required for the communication between Odoo and
  :doc:`WhatsApp Bussiness Account  <account_create_on_meta>`.
- :guilabel:`Users To Notify`: Under this tab user can enter the list of user. these list of users
  will be added to the Communication Channel, If Template used for such communication belongs to
  this WhatsApp Account.

After Entering all the above information user can click on the Button :guilabel:`Test Connection`.

.. image:: account_configuration/wapp-test-connection.png
   :align: center
   :alt: Test Connection

It will check with the :guilabel:`Meta Whatsapp API`, whether the entered details are correct
or not. If everything is correct then it will display the success message given as below.

.. image:: account_configuration/test-connection-success.png
   :align: center
   :alt: Test Connection Succesfull.

By clicking on the button :guilabel:`Sync Template`, user can fetch all the created
:doc:`WhatsApp Templates <../template/template_configuration>` on their :doc:`WhatsApp
Bussiness Account  <account_create_on_meta>`

.. image:: account_configuration/sync-template.png
   :align: center
   :alt: Template synchronization.

After clicking on :guilabel:`Sync Template`, User will be displayed notification of successful
synchronization of :doc:`WhatsApp Templates <../template/template_configuration>` on the
top right corner like shown below.

.. image:: account_configuration/sync-template-success.png
   :align: center
   :alt: Template synchronization Succesfull.

Once user synchronizes Whatsapp Template Succesfully, user will be able to see Whatsapp Templates
associated with the the Whatspp Bussiness Account by clicking on the stat button
:guilabel:`Templates`.

.. image:: account_configuration/wapp-account-templates.png
   :align: center
   :alt: Templates Associated to this Account.
