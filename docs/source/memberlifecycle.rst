.. _memberlifecycle:

Lifecycle of a Trident Member
=============================

Introduction
------------

This chapter serves as a training guide for members of a
trust group using a Trident user portal system. It clearly
shows what activities a member may pursue and attributes she
may manage. These activities include updating a member's
profile and other personal details, managing mailing list
memberships, using the wiki, etc.

.. _usermanagement:

User Attribute Management
-------------------------

This section will cover management of a user's attributes.

Profile Management
~~~~~~~~~~~~~~~~~~

Most of the details a regular member of a trust group can
modify about himself are found in the ``Profile`` page.
This page is accessible by clicking the ``Profile`` tab in
the second row of links at the top of the page, or the
``Profile`` link in the list of links on the user's home
page. Click either of those to get to the ``Profile`` page
that has editable attributes as can be seen in the next
three images.

.. figure:: images/trident/user-regular-shots/user-profile-1.png
       :width: 85%
       :align: center

       User profile, top

..

.. figure:: images/trident/user-regular-shots/user-profile-2.png
       :width: 85%
       :align: center

       User profile, middle

..

.. figure:: images/trident/user-regular-shots/user-profile-3.png
       :width: 85%
       :align: center

       User profile, bottom

..

On the profile page, details such as name, affiliation,
address, phone number, and airport can be added or modified.
A profile image can be uploaded. Longer-form attributes
can be edited, such as postal details and a biography. Failed
logins and some activity statistics are also tracked on a
member's profile.

Once a member has modified any of the editable attributes,
the ``Update Profile`` button must be clicked to save the
changes. The page will then refresh with the newly saved
information, as well as indicate how many fields were
updated and how many fields were not updated.

Other Personal Details
~~~~~~~~~~~~~~~~~~~~~~

Other personal details can be modified through the ``Details``,
``Languages``, and ``Username`` tabs found in the second row
at the top of any user-related page or in the list of links
found on a user's home page. We go through them all in this
section.

The ``Details`` page is a place to add any other details
that don't conform to the profile. Currently, the only
detail type is a callsign.

.. figure:: images/trident/user-regular-shots/user-details.png
       :width: 85%
       :align: center

       User details

..

The ``Languages`` page is the place to add languages a
member knows and her skill level at that language.

.. figure:: images/trident/user-regular-shots/user-languages-1.png
       :width: 85%
       :align: center

       User languages, choose language

..

.. figure:: images/trident/user-regular-shots/user-languages-2.png
       :width: 85%
       :align: center

       User languages, choose skill level

..

.. figure:: images/trident/user-regular-shots/user-languages-3.png
       :width: 85%
       :align: center

       User languages, updated language

..

The ``Username`` page allows a member to change her username.
This can affect external systems, so this change should be
used with care and caution. Enter the new username in the
field and use the toggle to confirm the change before
clicking the ``Change username`` button.

.. figure:: images/trident/user-regular-shots/user-username.png
       :width: 85%
       :align: center

       User username change

..

Password Change
~~~~~~~~~~~~~~~

The ``Password`` page allows a member to change her password,
provided she knows her current password (which she should,
since she is logged in already). When the member clicks the
``Change Password`` button, she is immediately logged out
and must login again, with the new password.

.. figure:: images/trident/user-regular-shots/user-password-change-1.png
       :width: 85%
       :align: center

       Define new password

..

.. figure:: images/trident/user-regular-shots/user-password-change-2.png
       :width: 85%
       :align: center

       Login with new password

..

Two Factor Authentication
~~~~~~~~~~~~~~~~~~~~~~~~~

The ``2FA Tokens`` page allows a user to add two-factor
authentication tokens. Types of two-factor authentications
include a variety of one-time passwords: time-based, HMAC-
based, and single-use. The user must give his current
password and a description for the token, as well as choose
which OTP type. Once those fields have been filled out,
click the ``Create`` button, and the new token will show
in the list of two-factor authentication tokens.

.. figure:: images/trident/user-regular-shots/user-2FA.png
       :width: 85%
       :align: center

       Two-factor authentication

..

Email Management
~~~~~~~~~~~~~~~~

The ``Email`` page covers a variety of things. It lists
email addresses tied to a user's account, showing if each
email address has a PGP key tied to it, whether it is
verified, whether it is the recovery email address associated
with the user's account, and with which trust group it will
be used.

It also provides a way to add a new email address, and
lists each group and associated email addresses for that
group.

.. figure:: images/trident/user-regular-shots/user-email-1.png
       :width: 85%
       :align: center

       Main email page

..

A user can edit attributes about email addresses associated
with his account by clicking the ``Edit`` button in the row
of the email address for which the edits should be made. 

.. figure:: images/trident/user-regular-shots/user-email-2.png
       :width: 85%
       :align: center

       Email edit page

..

Click the ``Make Recover Email`` button to make the
selected email address the recovery email address for the
user's account. 

Once this is completed, the button disappears and a check
box appears in the ``Recover`` row.

.. figure:: images/trident/user-regular-shots/user-email-3.png
       :width: 85%
       :align: center

       Make recover email

..

As can be seen, this is also the page where PGP keys are
to be added, and we will cover this in the next section.

Going back to the ``Email`` page shows another check box
in the list of email address.

.. figure:: images/trident/user-regular-shots/user-email-4.png
       :width: 85%
       :align: center

       Recover email confirmed

..

To add an email address, type it in the requested field:

.. figure:: images/trident/user-regular-shots/user-email-5.png
       :width: 85%
       :align: center

       Add new email

..

After clicking the ``Add Email Address`` button, the page
will refresh with the new address in the list at the top
of the page. Click the ``Edit`` button to make additional
changes.

.. figure:: images/trident/user-regular-shots/user-email-6.png
       :width: 85%
       :align: center

       New email attributes

..

A member must verify any new email addresses he manually adds.
Click the ``Verify`` button. This will send an email to the
provided address. The email will contain a verification code.
Copy and paste the code in the ``Verification Code`` field,
and click the ``Confirm`` button.

.. figure:: images/trident/user-regular-shots/user-email-7.png
       :width: 85%
       :align: center

       Verify email

..

Until the email address is verified, the list of email addresses
will retain an ``In Process`` status in the ``Verify`` column.

.. figure:: images/trident/user-regular-shots/user-email-8.png
       :width: 85%
       :align: center

       New email status

..

Remember, the "Edit" screen allows you to make any of your
available addresses the recovery email for your account.
Only one address may be the recovery email.

Since the ``dittrich`` user has not confirmed his new email
address yet, let's take a look at what happens when a user
does have multiple verfied email addresses.

A user can choose which email address will be associated
with each trust group of which she is a member. In the case
of the user ``mboggess``, she has two email addresses. Only
one address can be associated with a trust group at a time.
Since she has two email addresses, she must chose one to
be associated with the ``main`` trust group of which she is
a member.

.. figure:: images/trident/user-regular-shots/user-email-9.png
       :width: 85%
       :align: center

       Multiple emails

..

By choosing the second email address (the @uw email address)
to be the email address associated with the ``main`` trust
group, the list at the top of the page changes. It now
shows the @uw email address is associated with the ``main``
trust group, as indicated by the ``Groups`` column in the
list.

.. figure:: images/trident/user-regular-shots/user-email-10.png
       :width: 85%
       :align: center

       Email-group association swap

..



PGP Keys
~~~~~~~~

PGP keys can be downloaded and uploaded. They must stay
current for a user to be able to read any encrypted email
sent via the trust groups of which the user is a member.

To download all PGP keys tied to any emails associated with
a user's account, just click the ``Download All PGP Keys``
tab in the second row at the top of any ``User`` page, or
click the ``Download All PGP Keys`` link in the list of
links on the user's home page.

.. figure:: images/trident/user-regular-shots/user-pgp-download.png
       :width: 85%
       :align: center

       Download PGP keys

..

To add PGP keys, return to the ``Email`` page. Click the ``Edit``
button in the row of the email address of which you'd like
to associate a PGP key. In the ``PGP Key`` row, you will be
able to choose the PGP key file. Then click the ``Upload Key``
button.

.. figure:: images/trident/user-regular-shots/user-pgp-add.png
       :width: 85%
       :align: center

       Upload PGP key

..


Audit Log
~~~~~~~~~

The ``Audit Log`` page has no editable attributes. It shows
all activities accomplished by the user. 

.. figure:: images/trident/user-regular-shots/user-audit-log.png
       :width: 85%
       :align: center

       Audit log

..

Searches are possible. Additionally, only 10 activities are
shown at a time, so click the ``Forward`` button to see
older activities.


.. _usergroupmanagement:

Group Management
----------------

This section will cover group activities and attributes a
user may view or manage.

.. _viewableattributes:

Viewable Group Attributes
~~~~~~~~~~~~~~~~~~~~~~~~~

This subsection will cover attributes viewable from the
``Member``, ``Airports``, ``Contacts``, and ``Vouches``
tabs.

First of all, to view a list of groups of which a user is a
member, click the ``Group`` tab in the top row of any page.
This presents a page listing all groups of which a user is
a member.

.. figure:: images/trident/group-regular-shots/group-main-1.png
       :width: 85%
       :align: center

       Trust group list

..

To see more information about a certain group, click one of
the links in the list.

.. figure:: images/trident/group-regular-shots/group-main-2.png
       :width: 85%
       :align: center

       Trust group attributes list

..

This presents a page with a list of links to all attributes
viewable or manageable by the member. There are some activities
the member may take part in, such as nominating and vouching
for new group members, but, for the most part, a regular
member may only view these attributes. They are not allowed
to change attributes about the group or its members. One
notable exception is that members are allowed to start new
mailing lists. This activity, along with nominating and
vouching, will be covered in the next section. For now,
let's go over the attributes viewable by members.

The first link on the group home page, or the first tab in
the second row of all group-related pages is titled
``Members``. Click either the link or the tab to go to a
page listing all members in the current trust group.

.. figure:: images/trident/group-regular-shots/group-members.png
       :width: 85%
       :align: center

       Trust group members list

..

Click on any member's username link, and you will be taken
to their profile.

.. figure:: images/trident/group-regular-shots/group-member-profile-1.png
       :width: 85%
       :align: center

       Member profile, top

..

.. figure:: images/trident/group-regular-shots/group-member-profile-2.png
       :width: 85%
       :align: center

       Member profile, middle

..

.. figure:: images/trident/group-regular-shots/group-member-profile-3.png
       :width: 85%
       :align: center

       Member profile, vouches for

..

You may view any member's profile, provided you are in
their trust group. At the bottom of the profile, there are
lists of vouching activities the current member has been
part of: vouches he has made or vouches other members have
made for him. In the above example, another user vouched for
the user ``dittrich``, but he has not yet vouched for anyone.

In this next example, the user ``trident`` has vouched
for another member, but has not yet been vouched for by
any other member. We will discuss vouching in the section
on :ref:`manageableactivities`.

.. todo::

    Where should vouching go? User section or group section?

..

.. figure:: images/trident/group-regular-shots/group-member-profile-4.png
       :width: 85%
       :align: center

       Member profile, no vouches for

..

The ``Airports`` page shows a list of airports members of
the current trust group indicate as the airport nearest to
them.

.. figure:: images/trident/group-regular-shots/group-airports.png
       :width: 85%
       :align: center

       Airports list

..

Click on any airport abbreviation in the list, and you'll
be taken to a new page with a list of members who have
indicated the airport is the airport nearest to them.

.. figure:: images/trident/group-regular-shots/group-airports-phl.png
       :width: 85%
       :align: center

       Members with PHL airport

..

.. figure:: images/trident/group-regular-shots/group-airports-sea.png
       :width: 85%
       :align: center

       Members with SEA airport

..

The ``Contacts`` page shows a list of members of the current
trust group with their contact information, including
affiliation, email, telephone, and SMS.

.. figure:: images/trident/group-regular-shots/group-contacts.png
       :width: 85%
       :align: center

       Member contact list

..

The ``Vouches`` page shows a list of all vouches made for
members of the current trust group. This list indicates who
was vouched for and by whom and on what date the vouch was
made.

If no vouches have been made yet, you'll get a mostly
blank page:

.. figure:: images/trident/group-regular-shots/group-vouches.png
       :width: 85%
       :align: center

       No vouches

..

Once at least one vouch has been made, a list will appear:

.. figure:: images/trident/group-regular-shots/group-vouches-made.png
       :width: 85%
       :align: center

       Vouches made

..


.. _manageableactivities:

Manageable Group Activities
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The ``PGP Keys`` tab or link doesn't actually take you to a
new page, it just downloads all PGP keys for the current
trust group.

.. figure:: images/trident/group-regular-shots/group-pgp-download.png
       :width: 85%
       :align: center

       Download PGP keys

..

.. todo::

    This will cover the ``PGP Keys``, ``Mailing List``
    ``Wiki``, ``Files``, ``Nominate``, and ``Vouching
    Control Panel`` tabs.

..

