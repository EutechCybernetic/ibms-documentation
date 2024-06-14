# Chapter 3: Configuration of Prerequisites

This chapter describes the configurations of master data that are associated with IBMS application and other necessary configurations. Configurations will be done by the Application administrator.



{% hint style="info" %}
_Note –_

* _As the initial configuration, you need to do App Configuration, User Role Configuration and Process Configuration._
* _Next, **Location** and **Site** Configuration under the Location App and **Asset** Configuration under Asset App should be carried out before you start configuring Master data on IBMS App._
{% endhint %}

\
<mark style="color:blue;">It is recommended to follow the below stated sequence of configurations in IBMS application as some data become Prerequisites for some other configurations.</mark>\
\ <mark style="color:blue;">Most of the configurations have been described under this chapter, while some of the configurations found under Chapter 4 – Escalations and Chapter 5 – Register.</mark>

In IBMS application, the following tasks have to be carried out beforehand:

* [Configure Zones](chapter-3-configuration-of-prerequisites.md#configure-zones)
* [Configure Alarm Classes](chapter-3-configuration-of-prerequisites.md#alarm-classes)
* [Configure Alarm Severity](chapter-3-configuration-of-prerequisites.md#alarm-severity)
* [Configure System Types](chapter-3-configuration-of-prerequisites.md#system-types)
* [Configure Equipment Templates](chapter-3-configuration-of-prerequisites.md#equipment-templates)
* [Configure Point Templates](chapter-3-configuration-of-prerequisites.md#point-templates)
* [Configure Interface Driver Types](chapter-3-configuration-of-prerequisites.md#interface-driver-types)
* [Configure Interfaces](chapter-3-configuration-of-prerequisites.md#interfaces)
* [Configure Trend Groups](chapter-3-configuration-of-prerequisites.md#trend-groups)
* [Configure Data Sources](chapter-3-configuration-of-prerequisites.md#data-sources)
* [Configure Real-Time Reports](chapter-3-configuration-of-prerequisites.md#real-time-reports-configuration)
* [Configure Escalated Alarm Message Templates](chapter-3-configuration-of-prerequisites.md#escalated-alarm-message-templates)
* [Configure Alarm Escalation Disable Message Templates](chapter-3-configuration-of-prerequisites.md#alarm-escalation-disable-message-templates)
* [Configure Link Templates & Links](chapter-3-configuration-of-prerequisites.md#link-templates-and-links)
* [Configure Alarm Notification Groups](chapter-4-alarm-escalation.md#alarm-notification-groups) ( Described under Chapter 4 – Escalations)
* [Configure Alarm Escalation Matrix](chapter-4-alarm-escalation.md#alarm-escalation-matrix) (Described under Chapter 4 –Escalations)
* [Register Equipment](chapter-5-registering-new-items.md#register-new-equipment) ( Described under Chapter 5 – Register)
* [Register Systems](chapter-5-registering-new-items.md#register-new-systems) ( Described under Chapter 5 –Register)
* [Register Dashboards](chapter-5-registering-new-items.md#register-new-dashboard) ( Described under Chapter 5 –Register)

## Zones

An IBMS **Zone** is a wrapper around a “**Site**” which logically groups equipment on a Site.

This section describes the following:

1. [Configure Zones](chapter-3-configuration-of-prerequisites.md#configure-zones)
2. [Edit a Zone](chapter-3-configuration-of-prerequisites.md#edit-zones)
3. [Delete a Zone](chapter-3-configuration-of-prerequisites.md#delete-zones)
4. [Search Zones](chapter-3-configuration-of-prerequisites.md#search-zones)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark> ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) <mark style="color:blue;">on the Application Dashboard 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Zones 🡪 Zones**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">Search page</mark>

### Configure Zones

1. On the Zones search page, click the **New Zone** link. A dialog box to configure a new **Zone** appears.
2. Select the **Location** from the **Location** list box.
3. In the **Zone ID** box, type the name of the **Zone** that you want to configure.
4. Click **Add** to create the new **Zone**. Click ![](.gitbook/assets/Screenshot\_10.png)icon to close and abort the operation.

### Edit Zones

1. On the Zones search page, click the **Zone ID** you want to edit. Detailed page of the selected Zone will appear.
2. **Zone Details** tab displays IBMS Zone details.
   1. Move the cursor to the **Zone** **Details** section and click the **Edit** icon ![](<.gitbook/assets/Screenshot 2024-06-07 132020.png>)that appears.
   2. Edit the **Zone ID** as required.
   3. **Location** cannot be changed. If required, create a new **Zone** with desired **Site**.
   4. Click **Save**. Click **Cancel** to discard the changes.
3. **Subsystem Interface Connector** tab displays the IBMS Subsystem Interface configuration details.
4. **Equipment** tab displays the assets that are associated with the respective **Zone**.

### Delete Zones

1. Go to the Zones Search page and click the **Zone ID** you want to delete. Detailed page of the selected Zone will appear.
2. Click the **Delete this Zone** link or **Delete this Item**![](.gitbook/assets/icon\_4.png)  icon on the side bar.
3. A message box to confirm deletion appears. Click Delete to confirm deletion of the Zone, or to close the message box without deleting, click Cancel. If the Zone is in use, a message will appear stating that it cannot be deleted.

### Search Zones

1. On the Zones search page, to search by the **Zone** name, type the name of the **Zone** you want in the **Search Zones** box. Matching record/records will be filtered as you type.
2. To filter **Zones** by the **Site**, select the required **Site** from the box on the top right.
3. **Generate Report**: This is used to view the filtered results on a required format as a report.
   1. In the **Format** box, select the type of format(PDF/Word/Excel/Excel raw) you want.
   2. Click **Generate Report**. IBMS Zones Report will open with the filtered IBMS zones.
4. To go to the detailed page of a **Zone** in the search results, click its name.
   1. **Zone Details** tab shows the top-level location (**Site**) that this zone is configured for.
   2. **Subsystem Interface Connector** tab displays the IBMS Subsystem Interface configuration details.
   3. **Equipment** tab lists all the available equipment, relevant to the selected **Zone**. Clicking on the equipment name will navigate to the quick info page. Clicking on the Equipment name on the quick info page will show the **Asset** **details**.

{% hint style="info" %}
_Note – The_ _**Assets**_ _that have been registered as_ _**Equipment**_ _for the_ _**IBMS Zone,**_ _will be listed under the_ _**Equipment**_ _tab on the_ _**Zone Details**_ _page. To see details on registering an Equipment, please refer to the_ [_Register New Equipment_](chapter-5-registering-new-items.md#register-new-equipment) _section below._
{% endhint %}



{% hint style="success" %}
_Tip – To go back to the IBMS Home page, click the_ ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACUAAAAkCAIAAACBoGTxAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsIB3nSZJQAAAstJREFUWEftlTtMU1EcxltMmtZ2kJbWQSrBpK9FtBNqHSTqIo+IiNHBgiw+QgK9IMa3kTgI4oKVBB88Eg2VSeiKC/Ti0hYWazdMB0PtQlraTT9zmn9vL/TWNPQOhg7kcM73/X/3fP9z7lVubPxUyPirkJH1F7XL29nAy55nMplaW/tBD12EB+mdgXvwlLDLyLfv795O9vZwiUSC7EqJ+wDM4NNnUFut1v7bnn9ExuO/eH45sMQT5v6DuzU1B5ldivfk8WAsFmO69va2M2dPSyNDwfBSgF8Jr4hk42/GiueJKAgGtc83K2zDtuBgKLwVptfrheLt+7e4GOB5XlR04v2UqJFDz0egJFlXV4e746rIZTAYivDQ58mJKSaqrj7Acb1sjO3OfZ4nMwKIRqNQQk+TVfnVMW+zW6V4CM3rzcatVqu5Po/dYWtoOMU8CwtfgsEQBsIAoGdR46SQlxh7NZqCPMSF0NLpNBSA9fV7dDotxpevXMJGmQ0CICkAzED/Yvgldul9NUZenMn6Y/VYNZvNQl7e+RwdfU0NRydcruMkxQ6Gh0YymYzQjGeiGY1Gw2D4kRcx2GxWo7GKXLnz8vHDDMEam84JYVDjAjU3N4pgCIAOCMEQPnkxEMJgz/LwIOgNK1dXd7ilpUlYmo1x/7BE853X3HgIVBSeSYvFgvC3evP2h6x8M5/YFPrU0ekuZMASMsQqrr/TeZTJgGStwlW7eeu6BAxLe7q7b+ClJTgjXGXlvkIelUp1qLb2t0LRdrFVqHE6j6SSqdYL500mozRPOT09Pj/nZyLhi07aVvJqBVrFGoC/9FYtuVxRY/Y+4KqKDlJRZ2kCqe9DaRWlXWX/vovwytXVr5upzXJshWpqddrc9/bRw4FIJPeCLwfY4bB7uB5WWe485eYp/f7Z9fV4OWKkmvtNJtfJE+zf//0+yN2/Xd7OHl258/wDQS4ixFdKF9QAAAAASUVORK5CYII=) icon.
{% endhint %}

## Alarm Classes

**Alarm Class** is used to configure alarm Escalation Times of 5 Escalation Levels of each **Severity** for **Working Hour Escalations** and **After Hour Escalations**.\
E.g. If the Severity of an Alarm is Critical, you need to configure times of each Escalation Level which will be used as a base to send notifications to **Alarm Notification Groups** once an Alarm with the respective Severity is triggered. You need to configure the Escalation Times of Severity for Working Hour Escalations and After Hour Escalations.

This section describes the following:

1. [Configure Alarm Classes](chapter-3-configuration-of-prerequisites.md#configure-alarm-classes)
2. [Edit Alarm Class Details](chapter-3-configuration-of-prerequisites.md#edit-alarm-class-details)
3. [Delete an Alarm Class](chapter-3-configuration-of-prerequisites.md#delete-an-alarm-class)

{% hint style="info" %}
_Note –_ _**Prerequisite:**_ [_**Alarm Severities**_](chapter-3-configuration-of-prerequisites.md#alarm-severity) _should be configured before configuring_ _**Alarm Classes.**_
{% endhint %}

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark> ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Alarm Classes 🡪 Alarm Classes**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">search page</mark>

### Configure Alarm Classes

1. On the Alarm Classes search page, click the **New Alarm Class** link on the top right corner. New Alarm Class configuration window appears.
2. In the **Alarm Class Name** box, type a unique and appropriate name for the new **Alarm Class** and type in a description to the alarm class in the **Description** box.
3. Click **Add** to create the new Alarm Class. A new Alarm Class will be created and its detailed page will open.
4. To configure the Alarm Escalation Levels for each Severity for working hours, (Severity-wise Level configuration) go to the “**Working Hour Escalations**” tab.
   1. Click the respective **Edit** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABMAAAATCAIAAAD9MqGbAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwQAADsEBuJFr7QAAAZpJREFUOE+dkt1LwmAUxpvfNtxFhsuwbSzNFBJEQvEP6sJb8Sb6k7zpTpRAEJHIC0EmKM6J1Jah5GawxK+OTMTNTaX36t04v/O853kOIsujE4Mzm80KhaIs/yaT9zjuQRBku9BkhC2Xy1qN6fXeJWmczxfbbU5TqU8uFgtB6DscpyRJwn0+n1cqbyyrgnVIUBsMhrncC8uyOI7TNG02m0OhG5K82pZFduccDr9Lpcp4/DOdTjEMoyjK5UIJ4tLpdOybE/yoVmswGyiDlCiKgsBTlE+DQQvVa2Gkcvm13/9SeoOZVqsVjLXbbbtGqkiGafL853ZRPB5zu890/V+ToAbWNRpNi8WyqQsG/YEAbRTbmhyNxGz2meM4SN9kWv0EJhq9U+77NLvdniAInU6n1WpNJhOv9yISCdtsOuNtuqxago31OgMZwJEkiec/EokYiqJGamv/lDwzmScY1e+/DodvCcJHUYRmS3e7rDYBmHT6MZV6wDCXx3N+kFFpgjGQu5Lh/keq5oQPCAOY4zHtDh2pppQZxnWwy//JP6PZs9Poj0lmAAAAAElFTkSuQmCC)of a Severity and type the respective Escalation Time of Level 1.
   2. Type the required Alarm Escalation times of rest of the Escalation levels and click **Update**.
5. Configure the ‘After Hour escalation levels’ of each Severity under the “**After Hour Escalations**” tab as you configured the escalation levels under ‘Working Hour Escalations’.

### Edit Alarm Class Details

1. On the **Alarm Classes** search page, search for the required Alarm Class and click the Alarm Class name that you want to edit. Alarm Class detail page will open.
2. Move the cursor to the **Details** section and click the **Edit** icon![](<.gitbook/assets/Screenshot 2024-06-07 132020 (1).png>) that appears.
3. Edit the Alarm Class details required and click **Save**.
4. To edit the Working Hour and After Hour escalations, go to the respective tabs.

### Delete an Alarm Class

1. On the **Alarm Classes** search page, search for the required Alarm Class and click the name of it to go to its detailed page.
2. Click the **Delete this Alarm Class** link or **Delete this item** icon![](<.gitbook/assets/Screenshot\_11 (3).png>)on the side bar.

A message box to confirm deletion appears. Click **Delete** to confirm deletion of the Alarm Class, or to close the message box without deleting, click![](<.gitbook/assets/Screenshot\_10 (1).png>). If the Alarm Class is in use, a message will appear stating that it cannot be deleted.

## Alarm Severity

**Alarm Severity** is used to define the importance of each Alarm. Each Alarm has its Severity level. You can use the Alarm Severities to help you decide the order in which you should attend (prioritize) and investigate triggered alarms.

Typical Alarm Severities

<figure><img src=".gitbook/assets/Typical Alarm Severities_s3.png" alt=""><figcaption><p>Typical Alarm Severities</p></figcaption></figure>



Alarm Severities are color coded by configuring a color code for each Severity level. This is helpful for easy identification of alarms.

E.g. Severity “Critical” Color Code: “Red”

This section describes the following:

1. [Configure an Alarm Severity](chapter-3-configuration-of-prerequisites.md#configure-an-alarm-severity)
2. [Edit an Alarm Severity](chapter-3-configuration-of-prerequisites.md#edit-an-alarm-severity)
3. [Delete an Alarm Severity](chapter-3-configuration-of-prerequisites.md#delete-an-alarm-severity)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark> ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) <mark style="color:blue;">on the Application Dashboard 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Alarm Severity 🡪 Alarm Severities**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">page</mark>

### Configure an Alarm Severity

1. On the Alarm Severities page, click the **Add New Alarm Severity** link.
2. Type the name of the Alarm Severity and its Color code.
3. Enter the **Severity Weight.**
4. Click **Add**.

### Edit an Alarm Severity

1. On the Alarm Severities page, hover over the required Alarm Severity and click the **Edit** icon.
2. Modify details as required and click **Save.**

### Delete an Alarm Severity

1. On the Alarm Severities page, click the relevant **Delete** icon displayed along with the Alarm Severity you need to delete.
2. Click **Delete**.
3. If the Alarm Severity is in use, you will not be allowed to delete it.

## System Types

**System Types** are used as a grouping method to group IBMS System Pages. **System Type** will be used to filter System Pages based on System Types (e.g. BMC, LCS, ACS, etc.)\
System Types should be configured before registering Systems.

This section describes the following:

1. [Configure a System Types](chapter-3-configuration-of-prerequisites.md#configure-a-system-types)
2. [Edit a System Type](chapter-3-configuration-of-prerequisites.md#edit-a-system-type)
3. [Delete a System Type](chapter-3-configuration-of-prerequisites.md#delete-a-system-type)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark> ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) <mark style="color:blue;">on the Application Dashboard 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**System Types🡪 System Types search**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">page</mark>

### Configure a System Types

1. On the System Types search page, click the **New System Type** link.
2. On the System Type configuration page, type the name of the System Type and a description about it.
3. Click **Create**. Once created, its detailed page will open.

### Edit a System Type

1. On the System Types search page, click the required System Type name to go to its detail page.
2. Hover over the System Type tab and click the **Edit** icon![](<.gitbook/assets/Screenshot 2024-06-07 132020 (1).png>).
3. Modify details as required and click **Save.**

### Delete a System Type

1. On the System Types search page, click the required System Type name to go to its detail page and click the **Delete this System Type** link/**Delete** icon![](<.gitbook/assets/Screenshot\_11 (2).png>) on the side panel.
2. A message box to confirm deletion appears. Click **Delete** to confirm deletion of the System Type, or to close the message box without deleting, click ![](<.gitbook/assets/Screenshot\_10 (1).png>).
3. &#x20;If the System Type is in use, you will not be allowed to delete it.

## Equipment Templates

**Equipment Template** is a template for a collection of points for a particular type/brand/model of **Equipment.** Equipment Template logically groups points for a particular **Equipment type**.

This section describes the following:

1. [Configure Equipment Template](chapter-3-configuration-of-prerequisites.md#configure-equipment-template)
2. [Edit an Equipment Template](chapter-3-configuration-of-prerequisites.md#edit-an-equipment-template)
3. [Delete an Equipment Template](chapter-3-configuration-of-prerequisites.md#delete-an-equipment-template)
4. [Search Equipment Templates](chapter-3-configuration-of-prerequisites.md#search-equipment-templates)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark> ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) <mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Equipment Templates 🡪 Equipment Templates**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">search page</mark>

### Configure Equipment Template

1. On the Equipment Templates search page, click the **New Equipment Template** link. **New Equipment Template** dialog box appears.
2. In the **Equipment Template** box, type a unique and appropriate name for the new Equipment template.
3. In the **Description** box, type a suitable description on **Equipment template.**
4. Click **Create** to create the new **Equipment Template**. Click ![](<.gitbook/assets/Screenshot\_10 (1).png>)icon to close and abort the operation. Once an Equipment Template is created, its detailed page will be opened. On the detailed page, you can edit **Equipment Template Details** and configure Point Templates of the Equipment Template.

* To see how to edit Equipment Template Details, please refer to the [Edit Equipment Template ](chapter-3-configuration-of-prerequisites.md#edit-an-equipment-template)section below.
* To see how to configure Point Templates, please refer to the [Point Templates](chapter-3-configuration-of-prerequisites.md#point-templates) section.
* To see how to configure Link Templates, please refer to the [Link Templates](chapter-3-configuration-of-prerequisites.md#link-templates-and-links) section.
* To see how to configure Equipment, please refer to the [Equipment](chapter-5-registering-new-items.md#register-new-equipment) section.
* To see how to configure RT GUI, please refer to the [RT GUI ](chapter-3-configuration-of-prerequisites.md#rt-gui-tab-in-equipment-template)section.

### Edit an Equipment Template

1. On the Equipment Templates search page, click on the **Equipment Template** you want to edit.
2. On the Detail page, move the cursor to the **General** section and click the **Edit** icon![](<.gitbook/assets/Screenshot 2024-06-07 132020 (1).png>).
3. Edit the name of the **Equipment Template** as required.
4. Edit the **Description** as required.
5. **Enable Real-time Summary GUI:**
6. Click **Save**. Click **Cancel** to discard the changes.
7. Edit the Point Templates tab on the Equipment Template.
   1. [Add Point Templates to the Equipment Template](chapter-3-configuration-of-prerequisites.md#point-templates)
8. Under the **Link Templates** tab, [add **Link Templates** to the selected **Equipment** **Template.**](chapter-3-configuration-of-prerequisites.md#link-templates-and-links)
9. Under **Equipment** tab, [configure **Equipment** to the selected **Equipment Template**](chapter-5-registering-new-items.md#register-new-equipment)**.**
10. Under **RT GUI** tab,

#### RT GUI Tab in Equipment Template



### Delete an Equipment Template

To delete an **Equipment Template**;

1. On the Equipment Templates search page, click the **Equipment Template** that you want to delete, to go to its detailed page.
2. Click the **Delete this Equipment Template** link or **Delete** icon ![](<.gitbook/assets/Screenshot\_11 (4).png>)on the Side bar.
3. A message to confirm deletion appears. Click **Delete** to confirm deletion of the **Equipment Template,** or to close the message box without deleting, click ![](<.gitbook/assets/Screenshot\_10 (1).png>)icon on the top left of the message box.

#### If the Equipment Template is in use

If the selected **Equipment Template** is in use, a popup box appears with the message “**This Equipment Template is in use and cannot be deleted**”.

### Search Equipment Templates

1. On the Equipment Templates search page, type the name of the required **Equipment Template** in the **Search Equipment Templates** box. Matching record/records will be filtered as you type.
2. To go to the detailed page of an **Equipment Template** in the search results, click its name.
   1. **Details** tab shows the details of the selected **Equipment Template**.
   2. **Point Templates** tab lists all the **Point Templates** that have been configured for this **Equipment Template.** (To see how to configure Point Templates for Equipment Template, please refer to the [Point Templates ](chapter-3-configuration-of-prerequisites.md#point-templates)section)

## Point Templates

**Point Template** is a template for a particular **Point** on **Equipment Template**. After configuring an **Equipment Template**, you need to configure **Point Templates** for it.

{% hint style="info" %}
_Note – You should configure the relevant_ _**Equipment Template**, before you configure the required_ _**Point Templates**._
{% endhint %}



This section describes the following:

1. [Configure a Point Template](chapter-3-configuration-of-prerequisites.md#configure-a-point-templates)
2. [Edit a Point Template](chapter-3-configuration-of-prerequisites.md#edit-a-point-template)
3. [Delete a Point Template](chapter-3-configuration-of-prerequisites.md#delete-a-point-template)
4. [Search Point Templates](chapter-3-configuration-of-prerequisites.md#search-point-templates)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==)<mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Equipment Templates 🡪 Equipment Templates**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">search page🡪 Relevant</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Equipment Template**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Equipment Template Detail**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">page🡪</mark><mark style="color:blue;">**Point Template**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">tab</mark>

### Configure a Point Templates

This section helps you to configure Point Templates for Equipment Templates. These Point templates will be the points for equipment registered using the respective Equipment Template in the system.

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Equipment Templates** under **Configure** section. **Equipment Templates search** page will appear.
2. Search and click the required **Equipment Template** to which you want to add a new **Point Template**.
3. Then its Point Template detail page will appear. Click the **Point** **Templates** tab.
4. Click the **Add** icon![](<.gitbook/assets/Screenshot\_12 (1).png>). **New Point Template** dialog box appears.
5. In the **Point Name** box, type a unique and appropriate name for the new **Point Template**.
6. In the **Data Type** list box, select the relevant Data Type of the Point (**Value, Binary, Text** or **Multi-state**)**.**
7. Click **Add** to create the new **Point Template**. Click ![](<.gitbook/assets/Screenshot\_10 (1).png>)icon to close and abort the operation.

### Edit a Point Template

1. Go to the relevant **Equipment Template detail** page 🡪**Point Template** tab.
2. Click the name of the **Point Template** you want to edit. Details page of the selected **Point Template** will appear.
3. Go to **Details** tab.
4. **General**: To edit the **General** section, which contains the general data of the Point Template, hover over the **General** section click the **Edit** icon![](<.gitbook/assets/Screenshot 2024-06-07 132020 (1).png>).
   1. Edit the Point Template name if required.
   2. Type a description about **Point Template** under the **Point Template Description** box.
   3. Click **Save** to save the changes in the **General** section.
5. **Properties:** Hover over the **Properties** section and click the **Edit** icon![](<.gitbook/assets/Screenshot 2024-06-07 132020 (1).png>). Configure the following attributes of the Point Template and click **Save**.

<table><thead><tr><th width="262">Properties of Point Template</th><th>Description</th></tr></thead><tbody><tr><td>Data Type</td><td><p>Data Type of the Point</p><p>The Data Type can be any of these types (<strong>Value, Binary, Text</strong> or <strong>Multi-state)</strong>.</p></td></tr><tr><td>Read/Write State</td><td>Select Read or Write from the list box to denote the <strong>Point</strong> as read-only or write-only.</td></tr><tr><td>Units</td><td>Select the unit of measurement from the supported units in the combo box. (e.g. Point Template : Return Air Temperature, Units: Celsius (C) )</td></tr><tr><td>Valid Range (L:H)</td><td>This range will be the Valid Range (Low: High) of Point values. SSIF will send only Point Values within this valid range and rest of the Point values will be ignored.<br>E.g. 0.01 :1)</td></tr><tr><td>Display Range (L:H)</td><td>Display Range shows the formatted ‘Valid Range’ to give a proper look to the Point Values sent by SSIF to make it more convenient in usage (e.g. Valid Range is multiplied by 100 to make it ‘Display Range’).<br>Display Range (Low: High) e.g. 1:100</td></tr><tr><td>Round Off</td><td>Point Value will be rounded off up to this decimal point e.g. Round Off value is 1 -> if the real value is 2.46, the value will be rounded off to 1 decimal point and make it 2.5</td></tr><tr><td>Deadband</td><td>If the difference between the new Point Value and the existing Point value is plus or minus the Deadband, the new Point Value will be ignored. If the difference of the new Value falls between the deadband, the new Point value will be ignored. E.g. 0.5 and -0.5</td></tr><tr><td>Polling Frequency</td><td>Frequency of polling in seconds for the value you monitor from Sub System Interface.</td></tr><tr><td>Also apply for overridden points</td><td>Select this check box to apply the settings under <strong>Properties</strong> for overridden points</td></tr></tbody></table>

{% hint style="info" %}
_Note –_ _Reset Value Configuration section will be displayed under Point Template details only if the point’s_ **Read/Write State is ’Write’.**
{% endhint %}

**Reset Value Configuration**: Click the **Edit** ![](<.gitbook/assets/Screenshot 2024-06-07 132020 (1).png>) icon next to the **Reset Value Configuration** section to edit the following details.

1.  **Reset Value** – This is used to configure the Consultant recommended default value for Point Template.&#x20;

    _**Note**: You can override this consultant recommended Reset value at each Point level in the respective Point Template according to your requirement._
2. **Also apply for overridden points:** Select this check box to apply the settings under Reset Value Configuration for overridden points.
3. Click **Save.**
4. **Trend**: Click the **Edit** ![](<.gitbook/assets/Screenshot 2024-06-07 132020 (1).png>) icon next to the **Trend** section to edit the following details.
   1.  **Use Controller Based Trends ­­-** select this check box to use the trends that get recorded at Controller level.&#x20;

       _**Note:** If “Use Controller Based Trends” check box is selected, “Sample Interval” and “Change of Value (COV) trending” fields will be hidden._
   2. **Sample Interval (trending) –** Trending sample interval frequency in minutes
   3. **Change of Value (COV) trending –** Select this checkbox to use COV (Change of Value) of point to trend instead of poling for given trending intervals.
   4. **Also apply for overridden points** - Select this check box to apply the settings under **Trend** section for overridden points.
   5. Click **Save**.

### Add Alarm to Point Template

Alarm configuration under Point Templates varies due to the **Data Type** (e.g. Binary, Text, Value, Multi-state) of Point Template.

_**Prerequisites: Alarm Class and Alarm Severity**_

{% hint style="info" %}
_Note – Before you add_ _**Alarms**_ _to a **Point Template**, the required_ _**Alarm Classes**_ _should be configured under Alarm Class Configuration. (**Settings🡪Configure🡪Alarm Classes**) and_ _**Alarm Severity**_ _should be configured as well._
{% endhint %}

1. Access Point Template search page via Equipment Template Search page.
   1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Equipment Templates** under **Configure** section. **Equipment Templates Search** page will appear.
   2. Click the relevant **Equipment Template** which has the required **Point Template.**
   3. Click the **Point Templates** tab.
2. Access Point Template via Point Template Search page. (**Settings🡪 View🡪 Point Templates**)
3. Click the name of the **Point Template** you want and navigate to Point Template details page. Scroll down and go to the **Alarm** section.
4. Click on **Add** icon![](<.gitbook/assets/Screenshot\_12 (1).png>) under **Alarm** section. **Add Alarm** dialog box appears.
5. Select **Alarm Class** from the configured **Alarm Classes** in the list box (To see how to configure Alarm Classes, please refer to [**Alarm Classes** ](chapter-3-configuration-of-prerequisites.md#configure-alarm-classes)section).
6. Select the relevant **Alarm Severity** from the Alarm Severity box. Alarm Severities should be configured beforehand.
7. If the **Data Type** of the selected Point is “**Value**”;
   1. In the ‘**Alarm When’** dropdown box, select the relevant condition. (Equals, Is Not Equal To, Greater, Greater or Equal, Less, Less or Equal, Between, Between or Equal and Controller Based Alarms).
   2. Type in the relevant value/values in **Alarm When** textbox according to the selected above logical expression. E.g. If you have selected “Between” for “Alarm When”, you need to type two values to denote the range.
   3. In the ‘**Alarm When**’ dropdown box, select ‘Controller Based Alarm’ if the respective alarm is based on controllers.
8. If the **Data Type** of the selected Point is “**Binary**”;
   1. If the alarm is a ‘Controller based alarm’, select the ‘Controller based Alarm’ from **Alarm When** dropdown box.
   2. If the alarm is not a ‘Controller based alarm’, in the **Alarm When** textbox, type the relevant binary value (0 or 1) of the Alarm point.
9. If the **Data Type** of the selected Point is “**Text**”;
   1. In the **Alarm Value** box, type the required text to be checked as the condition.
   2. In the **Text Compare Mode** box, select the mode that you want to compare the text with. (e.g. Whether to see the given **Alarm Value** is **‘Not in’** or whether to see it **Contains** the **Alarm Value**)
10. If the **Data Type** is ‘**Multi-State**’;
    1. In the **Alarm Value** box, type the relevant value which is 0 – N.
11. Enter Alarm Deadband, Clearance Deadband, Alarm Delay and Clearance Delay accordingly. [(See the relevant details below)](chapter-3-configuration-of-prerequisites.md#alarm-observation-period-alarm-trigger-period-and-deadband-for-alarms)
12. Select **Enable only for working hours/ Enable only for non-working hours** checkboxes accordingly. [(See the relevant details below)](chapter-3-configuration-of-prerequisites.md#alarm-observation-period-alarm-trigger-period-and-deadband-for-alarms)
13. In the **Alarm Message** box, type the required alarm message to be relayed.
14. Click **Add.** Click ![](<.gitbook/assets/Screenshot\_10 (4).png>)icon to abort operation.

#### **Alarm Observation Period/ Alarm Trigger Period and Deadband for Alarms**



{% hint style="info" %}
_Note – If the alarm is a ‘**Controller based alarm**’, you are not required to enter the_ _**alarm**_ _**value**._
{% endhint %}

<table><thead><tr><th width="212">Field</th><th>Description</th></tr></thead><tbody><tr><td>Alarm Deadband</td><td>Alarm will be triggered only if the Alarm Value goes above this value (Alarm Deadband).<br>E.g. If alarm trigger value is >24 and Deadband is 0.5 then the alarm should get triggered only if the value goes above 24.5.</td></tr><tr><td>Clearance Deadband</td><td><p>Alarm will be cleared only if the Alarm value goes below this Value named as “Clearance Deadband”.</p><p>E.g. If alarm trigger value is >24 and Clearance Deadband is -0.5 then the alarm should get cleared only if the value goes below 23.5.<br></p></td></tr><tr><td>Alarm Delay</td><td>Alarm will be triggered only after the time configured as ‘Alarm Delay’ even though the Alarm conditions are met.</td></tr><tr><td>Clearance Delay</td><td>Alarm will be cleared only after the time configured as ‘Clearance Delay’.<br></td></tr><tr><td>Enable only for Working Hours</td><td>Alarm will be triggered only during the period configured as ‘Working Hours’.</td></tr><tr><td>Enable only for non-working hours</td><td>Alarm will be triggered only during the period configured as ‘non-working hours’.</td></tr></tbody></table>

#### Edit Alarm on Point Template

1. Go to the relevant **Equipment Template** detail page 🡪**Point Templates** tab.
2. Click the name of the **Point Template** you want and go to its details page.
3. Scroll down to Alarms section and click on ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAVCAIAAADJt1n/AAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsEBIwAp+wAAAHFJREFUOE9jfPn0KgO5gIlcjSB9Q1QzI8EASy9qhIfLzL565DAi4GdknZhBi08zfp34QpugTpyasepE8zB2zUTqxKKZeJ3omknSia4Z01eYItjjGWItsmr8OrE7G6KHoE6cAUaMTqBmwmkbT4YfovkZAMP6Krehe7yWAAAAAElFTkSuQmCC) icon on the far right corner of the alarm.
4. Edit the Alarm details as required.
5. Click **Update.** Click![](<.gitbook/assets/Screenshot\_10 (4).png>) icon to discard changes.

#### Add/Change Alarm Condition

When an Alarm Condition is added or changed at **Point Template level** or **Point level**, the system will validate the condition and pop-up validation messages if there are Active alarms for that particular Alarm Condition.

Validation confirmation messages will be popped- up due to the following situations;

* **When changing an alarm condition while there are active alarms**

It is required to check whether there are active alarms in the system for the respective alarm condition. If available, user should be notified and get the confirmation to disable the active alarms.

* **When adding Controller based alarms while having iviva alarms enabled**

When a Controller Based Alarm is added/enabled for a particular point template or point, it is required to have all other iviva based alarms to be disabled.\
E.g.\
_Validation Confirmation message at Point Template level_: “There are enabled iviva alarms for this point template. Please disable/remove them before adding a controller based alarm.”

* **When adding an iviva alarm while having enabled Controller based alarms**

System will allow to add/enable iviva based alarms, only if there are **no** Controller Based alarms or if the Controller Based alarms are disabled.

The above steps should be carried out to prevent the following issues;

* If you change an alarm condition while there are active alarms, current active alarm(s) gets junked and it may cause the point not to become alarmed again.
* SSIFs cannot handle both iviva and Controller based alarms at once, because controller based and iviva based alarms are handled in two channels.

#### Delete Alarm on Point Template

1. Go to the relevant **Equipment Template detail** page 🡪**Point Templates** tab.
2. Click the name of the **Point Template** you want and go to its details page.
3. Scroll down to **Alarms** section and click on the respective **Delete** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAbCAIAAAAPqBNFAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsYBbEG/PAAAAmNJREFUSEu1ll1P01AYx3vO6enLKDDKNhAQvNI5jHgBoiYk3PkJTExMjBd+JhMTL/wMXnrljaCJmqjZIjcKqOBgm4ORde1pezylpSvrC93AXixtz/P8nn//e84LqP4uczGXpenWbs2uNqmm2x2DMy2oyBRBlBtFUzl+bDgukb0HkVzz4MisbNnVRlLmkIxKc8J0PjImxKVU+/Ld/rEDEpCBIaCO4MWrfEbuCYfBZ0pI++1XmhrKcmnjUH/z2ag3Y7nUsrS1Mlc7SCe0GwUMQt5VzL+tYGLXh86nDXt7LxIqqOrUwwfu0PaLl7ahh8OoJEqrt5AkuEMel+zWyftKMJpXlJnHj5K199SAM3lpseimHPtLKals9vv54Xjr177vhqNX/7lnfdw4P9chTKqZO/OeD531ckSrAiDkcsnFjFqNfWswhkIo3b+NROzobb9a42yrt1EEcfbpk778dYP5pSKbLMf+hqDn8YQetk/+t3gM1Y3NZ8+tVsu9Yb/+m7gkqnXO5g4g3CaOpafm8QCUcArE6L9wgSx5XNYcF6LUhcDRIY/L1umL4jKJqJA94U6f0f/pq6J8FvI8i3fmhbNCvv7A6UYwHw40L/DdeTyhenoBQrg0l15UXCQsjLlQT697p62XaeKGllyYClhcXfA3pG4niEvXuOHMgKoBwMvF4C7X5TK/xXs3QFbpF00xwsslYdxpA/861blIFqWVm/ByIT0aKLK0soAnPVv9xOjzA/nTML9t0eZRQgFmKH99VrxyiQMRZ4JorotjpxNrp27vNykxuZaz+nGiAETMjY/wE2pYY1DEP+Td+jjtNYxiAAAAAElFTkSuQmCC) of the alarm that you want to delete.
4. If the respective alarm is in use, the system will not allow the user to delete it.

### Delete a Point Template

To delete a **Point Template;**

1. Go to the relevant **Equipment Template detail** page 🡪**Point Templates** tab.
2. Click the respective **Delete** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAbCAIAAAAPqBNFAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsYBbEG/PAAAAmNJREFUSEu1ll1P01AYx3vO6enLKDDKNhAQvNI5jHgBoiYk3PkJTExMjBd+JhMTL/wMXnrljaCJmqjZIjcKqOBgm4ORde1pezylpSvrC93AXixtz/P8nn//e84LqP4uczGXpenWbs2uNqmm2x2DMy2oyBRBlBtFUzl+bDgukb0HkVzz4MisbNnVRlLmkIxKc8J0PjImxKVU+/Ld/rEDEpCBIaCO4MWrfEbuCYfBZ0pI++1XmhrKcmnjUH/z2ag3Y7nUsrS1Mlc7SCe0GwUMQt5VzL+tYGLXh86nDXt7LxIqqOrUwwfu0PaLl7ahh8OoJEqrt5AkuEMel+zWyftKMJpXlJnHj5K199SAM3lpseimHPtLKals9vv54Xjr177vhqNX/7lnfdw4P9chTKqZO/OeD531ckSrAiDkcsnFjFqNfWswhkIo3b+NROzobb9a42yrt1EEcfbpk778dYP5pSKbLMf+hqDn8YQetk/+t3gM1Y3NZ8+tVsu9Yb/+m7gkqnXO5g4g3CaOpafm8QCUcArE6L9wgSx5XNYcF6LUhcDRIY/L1umL4jKJqJA94U6f0f/pq6J8FvI8i3fmhbNCvv7A6UYwHw40L/DdeTyhenoBQrg0l15UXCQsjLlQT697p62XaeKGllyYClhcXfA3pG4niEvXuOHMgKoBwMvF4C7X5TK/xXs3QFbpF00xwsslYdxpA/861blIFqWVm/ByIT0aKLK0soAnPVv9xOjzA/nTML9t0eZRQgFmKH99VrxyiQMRZ4JorotjpxNrp27vNykxuZaz+nGiAETMjY/wE2pYY1DEP+Td+jjtNYxiAAAAAElFTkSuQmCC) to the right of the **Point Template** name.
3. A message box to confirm deletion appears. Click **OK** to confirm deletion of the Point Template, or to close the message box without deleting, click **Cancel**.

### Search Point Templates

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Equipment Templates** under **Configure** section. **Equipment Templates** Search page will appear.
2. Click the name of the **Equipment Template**, which contains the **Point Template.**
3. Click the **Point** **Templates** tab and click a name of a Point Template to go to the detailed page.
4. Alternatively, click the **Settings** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) icon on the Home Page and select the **Point Templates** link under the **View** section. Point Templates search page will open.
   1. To search by the Point Template name, in the **Search Point Templates** box, type the name of the required Point Template. Matching result/results will be displayed as you type.
   2. To filter by any Equipment Template that Point Template belongs to, select the relevant Equipment Template name in the **Equipment Template** box.
   3. Click the name of a **Point Template** to go to its detailed page.

## Interface Driver Types

**Interface Driver Type** contains the common protocol configuration settings for a particular protocol for an interface.

{% hint style="info" %}
_Note –By default, the Interface Driver Types will be configured with the Interface installation._\
_Interface Driver Type Configuration is provided for configuring parameters for Custom Interfaces._
{% endhint %}

\
This section describes the following:

1. [Configure Interface Driver Types](chapter-3-configuration-of-prerequisites.md#configure-interface-driver-types)
2. [Edit an Interface Driver Type](chapter-3-configuration-of-prerequisites.md#edit-interface-driver-type-basic-details)
3. [Delete an Interface Driver Type](chapter-3-configuration-of-prerequisites.md#delete-an-interface-driver-type)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==)<mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Interface Driver Type 🡪 Interface Driver Types**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">search page</mark>

### Configure Interface Driver Types

1. On the Interface Driver Types search page, click **Add Interface Driver Type** link.
2. In the **Driver Type** box, type a unique and appropriate name for the new **Interface Driver Type**.
3. In the **Parameter List** box, type the relevant comma separated parameters.
4. Click **Create**. New Interface Driver Type will be created and its detailed page will open.

### Edit Interface Driver Type Basic Details

1. On the Interface Driver Type search page, click the required **Driver Type** to be edited. Its detailed page will open.
2. On the **Driver Type Details** tab, hover over the **Basic** **Details** section and click the **Edit** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAaCAIAAADE9MDgAAAAAXNSR0IArs4c6QAAARJJREFUSEtj/PTpBQMNABMNzAQZOWouJGAZSY+3b4+Orl656cK9jwz8ypYxiWE6IljiiFRzv11Z3DDx4CckkxRjOsrtMYwmKd4wDQWaf3/tnnuYDibeXKyGggz8/u072ebiNBRoooSEMHnm4jOUgc823EGCDHMJGJpfH63DhSU94A9fIgzlx14Q4DGXfEPxlA8UGYrH3O/fPuIo6fhsQWGKw/twPZjh8PvNc6CRwmY55akGfOhmE2coVvd+ujq/uu3AWyxGE20ornD4c39JPbrRpBiKJ3xRjI4xdSImTJEDDU86Qxhtnx5GMKLQYgJLOfn727ffcFUfP30TkRBhJbkWJLX8JdYC4stJYk2EqBtq5gIAW6OJ7GpOF98AAAAASUVORK5CYII=).
3. Edit other necessary details.
4. Click **Save**.

The following table shows the fields under **Basic Details** section.

| Field                                               | Description                                                                                |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Driver Type                                         | Displays the name given for the Interface Driver Type. You can edit the name if necessary. |
| Enable Downloading States Text checkbox             |                                                                                            |
| Enable Downloading Default Values checkbox          |                                                                                            |
| Parameters                                          | Displays the parameter list of the Interface Driver Type Edit the list if necessary.       |
| Point Address Decode Format (Real-Time GUI Tooltip) |                                                                                            |
| Custom Actions                                      |                                                                                            |

### Upload Binary Files to Interface Driver Type

On the Interface Driver Type details page, **Binaries** tab is used to upload the SSIF Binary files relevant to the respective **Interface Driver Type.**

To upload a Binary File;

1. On the Interface Driver Type detail page, click the **Binaries** tab.
2. Drag and drop the relevant SSIF Binary file (.Zip file) onto the given area on the page above the **Upload** button; or click on the given area to search and select for the relevant Binary file.
3. Click **Upload**.
4. **Assembly Name** (.exe name of the Interface), **Interface Version** and **Description** (if available in the Binary file) fields on the GUI will be automatically filled up by obtaining the respective details from the uploaded Binary file.

### Delete an Interface Driver Type

1. On the Interface Driver Type Search page, click the name of the Interface Driver Type that you need to delete, to go to its detailed page.
2. Click the **Delete** icon![](<.gitbook/assets/Screenshot\_11 (4).png>) or click the **Delete this Driver Type** link on the side panel under Driver Type Details tab. A message box to confirm deletion appears.
3. Click **Delete** to confirm deletion of the **Interface Driver Type**, or to close the message box without deleting, click the icon![](<.gitbook/assets/Screenshot\_10 (4).png>).
4. If the Interface Driver Type is in use, you cannot delete it.

## Interfaces

An **Interface** defines a communication channel between a **Point** and a **Sub System Interface**.

This section describes the following:

1. [Configure Interfaces](chapter-3-configuration-of-prerequisites.md#configure-interfaces)
2. [Edit an Interface](chapter-3-configuration-of-prerequisites.md#edit-an-interface)
3. [Delete an Interface](chapter-3-configuration-of-prerequisites.md#delete-an-interface)
4. [View Interfaces List](chapter-3-configuration-of-prerequisites.md#view-interfaces-list)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==)<mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Interfaces 🡪 Interfaces**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">search page</mark>

### Configure Interfaces

{% hint style="info" %}
_Note –You need to configure_ _**Interface Driver Types**_ _and_ _**Zones**_ _before configuring_ _**Interfaces**._
{% endhint %}

1. On the Interfaces search page, click the **Add a new Interface** link.
2. In the **Interface ID** box, type a unique and appropriate name for the new **Interface**.
3. In the **Driver Type** box, select the relevant Interface Driver Type. **Interface** will be created based on the selected **Interface Driver Type**.
4. In the **IBMS Zone** box, select the **Zone**, which is associated with the respective **Interface**.
5. Click **Create** to create the new **Interface**. A new Interface will be created and its detailed page will open. Except Proxy Server details, other fields on the Interface Details page will be filled with default values.

The following table shows the fields that appear on the **Interface Details** page. These are the values that will be applied to **Interface**.

<table><thead><tr><th width="345">Field</th><th>Description</th></tr></thead><tbody><tr><td>Configuration Refresh Interval (seconds)</td><td>The period of time in seconds between two events in checking the configuration change in Equipment Point address. This checking will be done by the <strong>Interface</strong>.</td></tr><tr><td>On-Demand (Default Value=0 means On Demand Support is Enabled)</td><td>If <strong>On Demand Support</strong> is enabled, <strong>Interface</strong> requests data from <strong>Subsystem</strong> only when real-time values of equipment are monitored. If it’s not On Demand (On Demand Support is disabled), the <strong>Interface</strong> will continuously request data from <strong>Subsystem</strong>.</td></tr><tr><td>Max Real-Time Queue Limit</td><td><p>Value Changes in Points will be sent as a batch to the Interface. This “Max Real-Time queue limit” field defines the maximum Value Change count that will be sent at one request. </p><p>e.g. Max Real-Time Queue Limit= 200 means, though there are more than 200 value changes in the queue, only 200 value changes will be sent to the Interface as 200 is the maximum count.</p></td></tr><tr><td>Max Resend Queue Limit</td><td><p>There will be a ‘Resend queue’ to queue Value Changes which will be used if there is a failure in sending normal Value Changes. A warning will be logged, if the Value change limit in the queue reaches this ‘Resend “queue limit.</p><p>e.g. 10000. This means if the no. of Value Changes in the queue exceeds 10000, the system will start logging a warning message.</p></td></tr><tr><td>Max Points to be downloaded per request</td><td>Maximum number of points to be requested and downloaded in one request.</td></tr><tr><td>Send Transaction Events (Default value is Disabled)</td><td>This shows whether the Subsystem events are captured or not.</td></tr><tr><td><p>Proxy Server</p><p></p><p>Proxy User Name</p><p></p><p>Proxy Password</p></td><td>If iviva is hosted in cloud, there may be a Proxy Server to assist in sending calls out to the Interfaces in local machines. These fields will be the Proxy Server settings.</td></tr><tr><td>Log Level</td><td>e.g 1 = Exceptions 2 = Exceptions+ Additional Transaction Data</td></tr><tr><td>Log Notification Threshold (minutes)</td><td>Time duration that the system waits after a log notification, before sending another error log notification. This helps to wait for the given threshold time, without sending the same error log notification.</td></tr><tr><td>Expiry Duration (minutes)</td><td>SSIF Heartbeat or Points will expire after this Expiry Duration in minutes.</td></tr><tr><td>Certificate Validation</td><td></td></tr><tr><td>TCP Message Bus</td><td></td></tr><tr><td>Cloud Local URL Validation</td><td></td></tr></tbody></table>

### Edit an Interface

1. On the Interfaces search page, search and click on the Interface ID to navigate to its details page.
2. Hover over the Interface Details section and click **edit** icon that appears. Edit the details on **Interface Details** tab as required and click **Save**. Click **Cancel** to discard the changes.
3. Go to the **Clusters** tab and create a **Cluster**.

#### Clusters

After creating an Interface, you need to create Clusters. If there is only one Instance of Interface (one machine), then you shall create only one Cluster. If there are two instances of the same **Interface** to be run on two machines, you shall create 2 Clusters. If the active Cluster stops working, then the other Cluster will become active.

**Create a Cluster**

To create a Cluster;

1. On the **Interface Details** page, click the **Clusters** tab.
2. Click the **Add** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAdCAIAAAAyxktbAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsUBWmncRwAAAetJREFUSEu1lltPwkAQhe2VREpBqAhvRIhR1ITE//8TTEzUaAwY3ri0BWyLCfQST2mzQKHrUpTwsnTOt8PMdM9yljU8+Z8PR0EHQTB3vi3LXi6Xvu+7ritJkiAIsiyraiGvnPI8T8lqPxogw5jMpjPQ08Tgls5KmlbGZntj9qCtL3s4HPu+x1IngRdq9Qu1WNgNTqIN3dR1gwW6GaNplfOqllBtFSsbF0TDMKFNRduWkyFfgoMWldykx1mjb4PB6NA6JOJXHfLJjzHaNCf0vrXbnbv7B3zRt7QMQABnC40Jm05mR6YcycEh8xpm7dhzyvwetCU46FkkCdG2HS8OoqQFO858jV4sFn8CjSCEFr4yH+9dP1h3Fo/Rq5vbDst+b69Pu9qr61ZckMQzFiIlhtDCWlPmKcM25DgMC/LZ6/9absw1vzrhXp4f6fvlcrnLZiMuCBYZskuTEFpYEEXJ/yGa0EJ0QVXofsG+MTigrec68gt2PSUSnK02IhQnVq/bZ3SWNLQgiM1Wg/hZfPJhXatVj0wchE2fXLsM/A0+lJkObcIhtwwM/lbRyhnoUO16Y4qjD0aMbz+aVq/XmBw9StnzPH1s4HJDOcc5jisWVSQriuLeP8p6e/I83/NcUZREUZBkuZj59pSh3LuSH1dj7tJo6AJVAAAAAElFTkSuQmCC). Cluster configuration page appears.
3. In the **Cluster ID** box, type a relevant name for the new **Cluster.**
4. Select the **Enabled** check box to enable the **Cluster**.
5. **Gateway IP** will be automatically updated, when the respective **Cluster** runs.
6. **Active Status** will be automatically updated, when the respective **Cluster** runs.
7. Click **Add** to save the Cluster.
8. Under the “Clusters” tab, the following details of each Cluster will be displayed;
   * Cluster ID
   * Enabled Status
   * Active Status/IP address of Gateway
   * Last Active Time/Active Since
   * Binary Updated Time/Binary Version
   * Service Status

{% hint style="info" %}
_Note –**Gateway IP**_ _and_ _**Active Status**_ _fields are Read-only and will be automatically updated when the respective Cluster starts running._
{% endhint %}

**Edit a Cluster**

To edit Cluster details;

1. On the respective **Interface Details** page, click the **Clusters** tab.
2. Click the **Edit** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAdCAIAAADZ8fBYAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsUBR2zs/wAAAkhJREFUSEu11m1vmzAQAOBhICyiQDogL6BmmjqtH6dO2v7/r5i6KF/XdYMkDS8lvJjuKMhQMA5DWlVVSXr3xDn7fOGi6PHNf/jh+tw8z8Mw9I5+HMcY51maCqLI80iSJFVTZFlGCDHWQ3Exxq6zOxwen/O8L5ND6PJyZpg6z/PUmLbred6v+985xkNqg3i0spaqqnaDX7mO47p/3CFiM8YwDXNutLLqGo1DgXMdF3Lpru/7I1ZKLMiFAjbpYr1Zlt3/fPiHj89x3WDYFXDI64W73x0GbpRuzj/ffr398s2yr1o0CODULpzT/b5+zlj1fLlarz+Ux3axtOQLpRUMDmjliygIAsY5JZmA2va6CQmC0HLBgX2qXN8LzlZ2vrRaKDRha6NKJPDDyo2imO2+oK+qmabpdnv3nFN6h2gI45RZUwq62XxPTidqFtFQjnsvAcNcdFfKQOGdiIagx/vW6/lH+Mjkv/CYjUIk3EdVfXlepLr21fs0SQAq6SEohAlCpaHpVKK6qqJdX9+UdBj6Z1daIkRDF4rcVwdFVSv6rnejWrlE48Jwv/mx7baG9HaKUHEPJEmCG43PODxQ3E83H8uGhL/Fzd+Njk9R9PQEvwNREMAhw6mwdeMd6hknZ1uRBIAATv30ZROFlbUYTlAjQWjeGNVxgxkF42Q0DbmtKVc3Bcwo3dBH0JDVnW/UefzAaO7mG8MBsOwB87jMgdZynJ139Fj3MsdpM800dVGkt+ug7ztZhuG08bAvAj+ZTLSZOub7zogSd1P+AiqMQ8NYhVu2AAAAAElFTkSuQmCC)to open the Cluster Details page.
3. Change the **Cluster ID** or Enabled/Disabled value if required.
4. The **Parameters** of the respective **Interface Driver Type** will be displayed. You may configure the relevant parameters according to the respective Cluster and the machine that it runs.
   1. To configure a parameter, type the relevant parameter value in the given box.
   2. Click **Set**.
5. Click **Update** to save the changes.

**Manually Activate/Deactivate/Refresh a Cluster**

1. On the respective **Interface Details** page, click the **Clusters** tab.
2. Click the respective ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAcCAIAAAD5mpj+AAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsMBDDN7wQAAAk1JREFUSEudll1zmkAUhot8ORERFNKIuWg17Q9ILvr//0aTeGUxE7Dy1WZUcPpul1kR2NWBC2eE8z579pzdfVf6+Ig+cZ7j8fgn+5skyW63L4r8cMhVVZFlRdc10zQHxk2v1+Np8V5qRRdFEQSbaBuBzhODa9mW605kWW6NaUEncbpev4EuyIh9knvy1LszR8NmcB0dvIdBEF4DrcY4zuT2s1tTnRWrGxfEMNxAy0WnSdYhX4aDFpWs0susUVnfX4vr8OXr4vHpB355YbUOlWjMSNy34dAcjx1A8XszGLTSQQCHfSJorLDtb+7qpqG73Y5p8kPOSxwctl7JCkGNVqtfF1eFpumO44ZhsN+fhmmqZjNvZJl4T7JO07PyN6MVWUFB8N73V2IuYrIsowSS9evLEluZl/V88d2ybPo1irbL15/i+eEYWDzMy6zzg2jjxQT3THEYg9fDSidKGilIcRShN5sgS5NrekhjGI2gcQ6I52j8LzSRFcXFWrPjkKAV9Vp0HG/FSeArDl4aQ9D9fl8ssO2yjWlyqgxPwmgEbRiGGK2qGg1IK0XnSRiNoIemIfYLdgZ4s3vPu8fe4XHBAe1UEOoXgsTX/orSRyNb03VBJ8FhWZZWAOXL8/JKZ+ElASd7+DZnflaefPg/nd5d7L44AISqT55cBv4GH+pMh7bmkGcGBn+bOOMOdKia3shxdP9NvPvZ8Gia502vcnSqyfM8eA/iOBXcQyRJsizTvXUVpdx+tem2X3FoUPX2hMHwgIJH07VR59tTh3I3Jf8AwMoaRR+VCaYAAAAASUVORK5CYII=)icon.
3. On the pop-up window, click **Activate** link to manually activate the respective Cluster.
4. If a Cluster is active and if you want to deactivate it, click the **Deactivate** link on the pop-up.
5. Click **Refresh** link to re-fresh the details in the Cluster.

(Or you can click ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACEAAAAoCAIAAAD/iQTwAAAAAXNSR0IArs4c6QAAAuhJREFUWEdj/PTpBQONARONzQcZP2oH8YE8GlY4wur3t48f0aQYCeSP3x8f3bx29fyFmy++f3tz7/5bVlklWU5OPiVDE0MdNSURLlTjfj8/tWzJTf3SWANkcdx2/H575cD6lSvP4MminOpOMeHuZnL8YBNBFkycdfybacakdCLs+Pbo+JKpC0+/JSbtsCh6Zqb5qf0+D7IAqIOTCDt+v7myZdaUnff/EGMBVA2nhPjvFy8hOjDtYEEz6dvdvWgWsChZ+rlYGqgrSvKzghV/e3P3/tXTe7fvuQb35/cXL/G4CCU+fr+5sKRtxrFPcPXidmmZwWYSaDELkf795taexdPXXf2OZjqmP5Dz4Meb21cjLGBRC68sj8VhAdBcVhFFA2ttPiJCFGHH7+cXtx+F+17cLifeXhmrB6DeAKeiMwg/47YMbsfv51eO34LFM59VoJ+OMCT4sQFoMiUq3SHK9t9v7194DDNO3MpeDZLmKbcAaAIszj9end84GRoZEk4lVWHqeMKJiDhAVgINq9+/P338BhPnl8ATTCSaD1IOi4/f377BIoOTj48Vd1RQYAcrFxcsO37/9On3bzKMwqkF6g9WVj5+eAR8fPGWFnYwcAkrScI88uLqlefwyKGCh2DxwSqsaCALM+/lsYO30CsaCuyC50FWSR1LNZhPPh1bvek81QIMUZawSpr4OYjDnPv20MyFB+8SCrHfb88v7myaefwRXoXMlZUlMHNZ+SUE358/8xhSkv57e/XIhY8SKqrS0DIdLbSA5e6uOX2LTr/+9OzisZu/VfVURDiYsYYoel377e6OCd0bkCsoFllLP0/U+uPR/avHUOoPoNES9rklsdpYSyDM+pycelDYND4/1lISR/GDvc3w7dGhJVOXEVufu6SkBRuI4C4a8LVLbh5YvwRvu4RFyTYmJtBajkDxSUr76uO9+y+4ZJUkgO0rWUMTMyztK+yZiJAdFGQ9uNbRNjXxoTgaVsSHFQABfkpQREVKswAAAABJRU5ErkJggg==) icon of a selected Cluster to refresh the details in the Cluster).

The following additional functional options will be available for each selected Cluster under Cluster options, when the “SubsystemInterfaceUpdate.exe” is running as a background service.

* Restart Service
* Start Service
* Stop Service
* Install Service
* Uninstall Service
* Update Service

To select an option under a Cluster;

1. Click the respective ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAcCAIAAAD5mpj+AAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsMBDDN7wQAAAk1JREFUSEudll1zmkAUhot8ORERFNKIuWg17Q9ILvr//0aTeGUxE7Dy1WZUcPpul1kR2NWBC2eE8z579pzdfVf6+Ig+cZ7j8fgn+5skyW63L4r8cMhVVZFlRdc10zQHxk2v1+Np8V5qRRdFEQSbaBuBzhODa9mW605kWW6NaUEncbpev4EuyIh9knvy1LszR8NmcB0dvIdBEF4DrcY4zuT2s1tTnRWrGxfEMNxAy0WnSdYhX4aDFpWs0susUVnfX4vr8OXr4vHpB355YbUOlWjMSNy34dAcjx1A8XszGLTSQQCHfSJorLDtb+7qpqG73Y5p8kPOSxwctl7JCkGNVqtfF1eFpumO44ZhsN+fhmmqZjNvZJl4T7JO07PyN6MVWUFB8N73V2IuYrIsowSS9evLEluZl/V88d2ybPo1irbL15/i+eEYWDzMy6zzg2jjxQT3THEYg9fDSidKGilIcRShN5sgS5NrekhjGI2gcQ6I52j8LzSRFcXFWrPjkKAV9Vp0HG/FSeArDl4aQ9D9fl8ssO2yjWlyqgxPwmgEbRiGGK2qGg1IK0XnSRiNoIemIfYLdgZ4s3vPu8fe4XHBAe1UEOoXgsTX/orSRyNb03VBJ8FhWZZWAOXL8/JKZ+ElASd7+DZnflaefPg/nd5d7L44AISqT55cBv4GH+pMh7bmkGcGBn+bOOMOdKia3shxdP9NvPvZ8Gia502vcnSqyfM8eA/iOBXcQyRJsizTvXUVpdx+tem2X3FoUPX2hMHwgIJH07VR59tTh3I3Jf8AwMoaRR+VCaYAAAAASUVORK5CYII=)icon and select the required option from the pop-up menu.

**Delete a Cluster**

1. On the respective **Interface Details** page, click the **Clusters** tab.
2. Click the respective **Delete** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAbCAIAAAAPqBNFAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsYBbEG/PAAAAmNJREFUSEu1ll1P01AYx3vO6enLKDDKNhAQvNI5jHgBoiYk3PkJTExMjBd+JhMTL/wMXnrljaCJmqjZIjcKqOBgm4ORde1pezylpSvrC93AXixtz/P8nn//e84LqP4uczGXpenWbs2uNqmm2x2DMy2oyBRBlBtFUzl+bDgukb0HkVzz4MisbNnVRlLmkIxKc8J0PjImxKVU+/Ld/rEDEpCBIaCO4MWrfEbuCYfBZ0pI++1XmhrKcmnjUH/z2ag3Y7nUsrS1Mlc7SCe0GwUMQt5VzL+tYGLXh86nDXt7LxIqqOrUwwfu0PaLl7ahh8OoJEqrt5AkuEMel+zWyftKMJpXlJnHj5K199SAM3lpseimHPtLKals9vv54Xjr177vhqNX/7lnfdw4P9chTKqZO/OeD531ckSrAiDkcsnFjFqNfWswhkIo3b+NROzobb9a42yrt1EEcfbpk778dYP5pSKbLMf+hqDn8YQetk/+t3gM1Y3NZ8+tVsu9Yb/+m7gkqnXO5g4g3CaOpafm8QCUcArE6L9wgSx5XNYcF6LUhcDRIY/L1umL4jKJqJA94U6f0f/pq6J8FvI8i3fmhbNCvv7A6UYwHw40L/DdeTyhenoBQrg0l15UXCQsjLlQT697p62XaeKGllyYClhcXfA3pG4niEvXuOHMgKoBwMvF4C7X5TK/xXs3QFbpF00xwsslYdxpA/861blIFqWVm/ByIT0aKLK0soAnPVv9xOjzA/nTML9t0eZRQgFmKH99VrxyiQMRZ4JorotjpxNrp27vNykxuZaz+nGiAETMjY/wE2pYY1DEP+Td+jjtNYxiAAAAAElFTkSuQmCC) to the right to delete Cluster from the Interface.

{% hint style="info" %}
_Note –If a Cluster is active,_ _**Delete**_ _icon_ ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAbCAIAAAAPqBNFAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsYBbEG/PAAAAmNJREFUSEu1ll1P01AYx3vO6enLKDDKNhAQvNI5jHgBoiYk3PkJTExMjBd+JhMTL/wMXnrljaCJmqjZIjcKqOBgm4ORde1pezylpSvrC93AXixtz/P8nn//e84LqP4uczGXpenWbs2uNqmm2x2DMy2oyBRBlBtFUzl+bDgukb0HkVzz4MisbNnVRlLmkIxKc8J0PjImxKVU+/Ld/rEDEpCBIaCO4MWrfEbuCYfBZ0pI++1XmhrKcmnjUH/z2ag3Y7nUsrS1Mlc7SCe0GwUMQt5VzL+tYGLXh86nDXt7LxIqqOrUwwfu0PaLl7ahh8OoJEqrt5AkuEMel+zWyftKMJpXlJnHj5K199SAM3lpseimHPtLKals9vv54Xjr177vhqNX/7lnfdw4P9chTKqZO/OeD531ckSrAiDkcsnFjFqNfWswhkIo3b+NROzobb9a42yrt1EEcfbpk778dYP5pSKbLMf+hqDn8YQetk/+t3gM1Y3NZ8+tVsu9Yb/+m7gkqnXO5g4g3CaOpafm8QCUcArE6L9wgSx5XNYcF6LUhcDRIY/L1umL4jKJqJA94U6f0f/pq6J8FvI8i3fmhbNCvv7A6UYwHw40L/DdeTyhenoBQrg0l15UXCQsjLlQT697p62XaeKGllyYClhcXfA3pG4niEvXuOHMgKoBwMvF4C7X5TK/xXs3QFbpF00xwsslYdxpA/861blIFqWVm/ByIT0aKLK0soAnPVv9xOjzA/nTML9t0eZRQgFmKH99VrxyiQMRZ4JorotjpxNrp27vNykxuZaz+nGiAETMjY/wE2pYY1DEP+Td+jjtNYxiAAAAAElFTkSuQmCC) _will not be displayed along with the respective Cluster details._
{% endhint %}

#### Transactions tab

Transaction tab is used to log the transactions associated with Cluster related functionalities.

Cluster commands will be logged under the **Transaction** tab.

System will log the following details of cluster commands.

* Transaction Time: Displays the date & time that the transaction occurred
* Transaction Description: Displays the type of the option (Cluster Commands)
* User ID: User ID of the user who performed the function
* Description: Displays whether the transaction (command) is successful

You can filter the transaction records by giving Start Time (Start Date & Time) on the side panel.

To generate a report on Interface Transactions:

1. On the side panel, filter the transaction records by giving Start Time (Start Date & Time).
2. In the **Format** Box, select the report format (PDF/Word/Excel/Excel-Raw) as you want.
3. Click **Generate Report.**

#### Debug Tab

Debug tab displays the debug information which is managed by SSI when troubleshooting.

### Delete an Interface

1. On the Interfaces search page, click the name of the **Interface** that you need to delete, to go to its detailed page.
2. Click the **Delete** icon![](<.gitbook/assets/Screenshot\_11 (4).png>) or the **Delete this Interface** link on the side panel.
3. A message box to confirm deletion appears. Click **Delete** to confirm deletion of the **Interface,** or to close the message box without deleting, click the ![](<.gitbook/assets/Screenshot\_10 (4).png>) icon. If the selected Interface is in use, a message will appear stating that it cannot be deleted.

### View Interfaces List

1. On the Interfaces search page, to search by **IBMS Zone**, select the relevant IBMS Zone from the list box.
2. To filter **Interfaces** by **Driver Types**, select the required Driver Type.
3. To filter only the **Interfaces** that are active, select the **Show Active Interfaces** check box.
4. You can filter the required Interfaces and **Update/Restart/Refresh** them by clicking the respective button on the Side bar.
5. **Generate Report**: This is used to generate the current report in PDF/Word/Excel/Excel-raw formats.
   1. In the **Format** box, select the type of format you want.
   2. Click **Generate Report**.

To view the name of each data column in the Interface Search page, click the ![](<.gitbook/assets/Screenshot\_14 (4).png>) icon on the Toolbar.

<table><thead><tr><th width="219">Field (Column Name)</th><th>Description</th></tr></thead><tbody><tr><td><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAIAAACQkWg2AAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxwAADscBOJIvdgAAAfNJREFUOE+Vkj9vE0EQxd/6bu8cx04IF5ARwTiJRUWQEAUCCYIUCRpCQZEG8RUiUYCoI/gANCh9RAGIAolUCAosGgIUQSAgCnEioxAby38P27t3t8za5+AiKdh25s1785tlhcI2/uexPoFinsvLK1bxpVn/Aig/fqI9OiNHzio+DBbpju0JAs+sf45tPLTLWVgjsBwqQZQgyjIx5U7eksOnEbF2Bcqsrsa/3+PiF1LXcXwOgQcEMOLYeor8c4/ZjcxdsgIztAOTtaFP81Z7E6cWcGwWjOPVZcgarrzVIQpv8PGOZIna1IMgmtTJeOWDVX2HsWsYuwojqpsa66iv0RowLBy+SJ7c/cpLWq8FtKXOTUnMgT2AkYZmDRyxS69DgWZCWx44uS/eRAbRQ4a7Hgq0NTHpgdtDRiVdpbZOJOKtCVa//WsdTCMxoad0X2MDraIfS4eCtjNDvLH5BH67cxuG9BzGb4aegUT+BZrbwrkUCqRzTgydwdYz5Je1RinkHuPHElQAX2Ani9wjGcsIZ7p3OBXwykp87b4ZNDF+A0dn0drR3YMp/FwmZ0823cnbYnQaEXP3awheeR/LLVr1VUSTxETnaRUpibRTfybmxcHzXeh9n0/5EVHiv7PEu0NQ0ZaUWzgXAjtJs7v79//Wfc/QX/gL4nXRpcsavCsAAAAASUVORK5CYII=" alt=""> New Version is available</td><td>This is to show an Exclamation icon<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAIAAACQkWg2AAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxwAADscBOJIvdgAAAfNJREFUOE+Vkj9vE0EQxd/6bu8cx04IF5ARwTiJRUWQEAUCCYIUCRpCQZEG8RUiUYCoI/gANCh9RAGIAolUCAosGgIUQSAgCnEioxAby38P27t3t8za5+AiKdh25s1785tlhcI2/uexPoFinsvLK1bxpVn/Aig/fqI9OiNHzio+DBbpju0JAs+sf45tPLTLWVgjsBwqQZQgyjIx5U7eksOnEbF2Bcqsrsa/3+PiF1LXcXwOgQcEMOLYeor8c4/ZjcxdsgIztAOTtaFP81Z7E6cWcGwWjOPVZcgarrzVIQpv8PGOZIna1IMgmtTJeOWDVX2HsWsYuwojqpsa66iv0RowLBy+SJ7c/cpLWq8FtKXOTUnMgT2AkYZmDRyxS69DgWZCWx44uS/eRAbRQ4a7Hgq0NTHpgdtDRiVdpbZOJOKtCVa//WsdTCMxoad0X2MDraIfS4eCtjNDvLH5BH67cxuG9BzGb4aegUT+BZrbwrkUCqRzTgydwdYz5Je1RinkHuPHElQAX2Ani9wjGcsIZ7p3OBXwykp87b4ZNDF+A0dn0drR3YMp/FwmZ0823cnbYnQaEXP3awheeR/LLVr1VUSTxETnaRUpibRTfybmxcHzXeh9n0/5EVHiv7PEu0NQ0ZaUWzgXAjtJs7v79//Wfc/QX/gL4nXRpcsavCsAAAAASUVORK5CYII=" alt="">, if the updated Interface details are not downloaded by SSIF, after an Interface is updated.</td></tr><tr><td>Interface ID</td><td>Name of the Interface</td></tr><tr><td>Active Cluster</td><td>Name of the Active Cluster. This will be shown only if the Interface is active.</td></tr><tr><td>Driver Type</td><td>Type of the Driver associated with the Interface</td></tr><tr><td>Zone</td><td>Name of the Zone associated with the Interface</td></tr><tr><td>Active Status/ Time</td><td><p></p><p>Status of the Interface and the Date Time if Status is Active.</p><p>If Active 🡪 Active +&#x3C;Last time that the interface was on Active status><br>E.g. Active<br><strong>6-June-2019 11:24 AM LK</strong></p><p>If Inactive 🡪 E.g. Inactive</p></td></tr><tr><td>Service Status/Time</td><td>Status of the associated Service and the last time that the Service’s status returned<br>E.g.<img src=".gitbook/assets/Service StatusTime_s4.png" alt=""></td></tr></tbody></table>

## Trend Groups

\
A **Trend Group** is a collection of **Trend Points** with same unit of measurement. (e.g. Temperatures, percentage, pressure) This section describes the following:

1. [Configure Trend Groups](chapter-3-configuration-of-prerequisites.md#configure-trend-groups)
   1. [Add Points to the Trend Group](chapter-3-configuration-of-prerequisites.md#add-points-to-the-trend-group)
   2. [Edit Points on Trend Group](chapter-3-configuration-of-prerequisites.md#edit-points-on-trend-group)
   3. [Delete Points from Trend Group](chapter-3-configuration-of-prerequisites.md#delete-points-from-trend-group)
2. [Edit a Trend Group](chapter-3-configuration-of-prerequisites.md#edit-a-trend-group)
3. [Delete a Trend Group](chapter-3-configuration-of-prerequisites.md#delete-a-trend-group)
4. [View Trends of Trend Group](chapter-3-configuration-of-prerequisites.md#view-trends-of-trend-group)
5. [Dynamic Trend Groups](chapter-3-configuration-of-prerequisites.md#dynamic-trend-groups)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">icon</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==)<mark style="color:blue;">🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section 🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Trend Groups 🡪 Trend Groups**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">search page</mark>

### Configure Trend Groups

1. On the Trend Groups search page, click the **Add New Trend Group** link. **New** **Trend Group** configuration page opens.
2. In the **Trend Group Name** box, type a unique and appropriate name for the new **Trend Group**.
3. In the **Location** box, select the relevant Location where the **Trend Group** is configured for.
   1. To select Location from the Location list box, click on the **Location** box and select the location from the populated list.
   2. To select the location from the Location search page, click the **Search** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAdCAIAAAAyxktbAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsUBWmncRwAAAsZJREFUSEu1ltlv2kAQh+MLUuGDy2AX0lAljSOVPPT/f+tLq0rtQ6tWhAQlqUi5A75IYnvtjjEyxqzBQcpKSGh35tvZ387smNC0/sHrDPJ1sD6V2BK167qGYeqaYVnPCLm2ZTMZhqLITCbL8SzL5khyW2R4NEJoPJpMp6rnuknHIkiyUBDKYomiKKwNBq2q2qA/RA5KoxVJkZJcFQR+0ziOHo0m4+E4DTRqA7GLlXLMa02s/bhABPXANxGtafoe8YY48AUlo/Rl1I7j9HuDl+oQs4cbAk44udR6OACNH5LQYlXOCwWaYeamMRz2H+dmkmWpXKxUxWDVR0P+ti872DwD3JnykWVXCeB53t+7zqD/D59wJHmmnAT57v903UjK38b7U+CORv0f3798+/q59een49jHjVOOF7Bo4MCdBUs+2tDxB8xmD4tF0TC0m07bsW2w1LTZ9XUL/lSqcpImpjFfoZ+enrF22cM3MK+qs+iqrs4QcnI5Ngkd0vyo4Yz403l+ldP0Wh2T8IiQlL04BHaENB/tIvxDoeuabVuiKAXhB6NebxAEoarTJHRIW1wllfCAed7tzRXE2Lz49O74pCLJyvmFJNfARRAKED6WDs/WSmuaZpJCmD5Mrtq/YRWIjcYHIV8IpOA4QTlvYukMs6T5eX3f7WnrNbq5U45l4ZmeP85ty1KUJiSfaRqXrV9B5kQHL/C1up8/Pno2U3v3L2hjEOzRUaPbvcU+vHJNyuf9rPd14XkuFChJmei8i9DdbQfLBQ7QVlpDXUK/SAPdaQOcsKstbxOeFWo9f3dSNg2AAJxwfommaboqVfbARV2AAJw4epGqPPShvengG+uQa8UC/S16ovTbgNdmb8R3dOg4SdUf2w9SQn6brqMHnlBy0EY1Vd/yHXJAEEKeF8VSWH7xXVN+PTkOcmyHZuCeKIbJ8AK38+vpP95zTfwP85EsAAAAAElFTkSuQmCC) icon and select the location you want from the Location search window that appears.
   3. To select the Location from the pinboard, click the **Pin** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB8AAAAeCAIAAABbkFLLAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxAAADsIBw3GpnQAAAnpJREFUSEu1lttu2kAQhuMTEPAhAUxCW9pEiZJUanPR3PT9X6FRBYlaJBoIxxB7zSH41D/aysbG3mKk+M72P9/Mzs7sLGea/b03e/g3I7+Cuf/G7nmeZc2Iaa1WL67r2StbykmCwOdyeUWVZbnE86khsuiu645Hk+nU8D0vbYkczx8ealW9IgjCpiaVbhjmoD90HXeb1PECf1w/0jQ1Jk6mj0aT8XC8DXddgxXoter6l4SU7YYGFGmELYtummSHqAMibJHS4DUSu+M4/cdB1oTE9NgtcOjHCP1pMt1yGxkRgAAOFYS7irq+a/1iFB/UsqI2Gieyoi0Xi16vg61PdIMyvbg8Qx+EsRNisdH7xdLV52tFPeA4br9YPDu/qtXqiXRwsH+RzFhkxlgvwnn/4WOsLRufTtNMZtY8Ql8uX9KksqJ8u/leLusxgSCI8JpoRWnhP8ex0+gWId1uZ/PvYjFPSyalhXTPTT1MoBsOHjud3+sOfN9/+NNOC4jSQjrOijRpuaJ/vb55nk4CB4QYzeaP6VOkM9fNacZCoihKifRKtYbyyOcLF5df+o9dOEDU93c/ifHMqAJJeqWF9EIhn6g+OT1HCaIb2u37Pd/v9x5azVvHTt0kCqG0kF6Si5t0LBCFsVzOW63bIFjT+NeKjNgpLVuvMnCxpMd7FZ2CKbOlPVsGDu27SJ1UqmVBTBhgmVyCAA41idBFUTw6rmVibYpBACeBjk+YjRhgOzuA7fp0TeggzMZgaZncwCo2V1l3Aswp9vEQ+Ebh1t9tfSegZrZtYwqbBmGd+xynHai6XqHNGXuy3cUcx3VsR5SwbYIk5VRN2f0ulinpieK/3HY0Z0N+lZ4AAAAASUVORK5CYII=) and select from the pinned item list.
4. Click **Create** to create the new **Trend Group**. Configured Trend Group name will be displayed on the **Trend Groups** page. Trend Group Detail page will open. Trend Group detail page will consists of the following tabs.
   * Details – Shows the main details such as **Trend Group Name** and **Location**
   * Points – Shows the **Configured Points** in the **Trend Group.** Type the required Point name in the **Search Points** search box, to filter Points by Point name.
   * Trend – Shows the Trends associated with the Trend Group

#### Add Points to the Trend Group

You can add configured points to the created Trend Group.

1. Go to the Trend Group Detail page.&#x20;
2. On the Trend Group details page, click the **Points** tab.&#x20;
3. Click the **Add** ![](<.gitbook/assets/Screenshot\_12 (2).png>)icon. Points search window will open to add configured Points to the respective **Trend Group.** Point configuration should be done first in order to list the configured points in the Point Search Window. Refer [**Configure Point Templates**](chapter-3-configuration-of-prerequisites.md#point-templates) section for more details on configuring points.&#x20;
4. Select the **Point Name** from the **Points** search page. **Points** can be added from the pinboard as well.&#x20;
5. Click the **Point Name** to add the selected **Point**.

#### Edit Points on Trend Group

1. Go to the Trend Group Detail page. Click the **Points** tab.
2. Click the **Point Name** to go to the relevant Point details page.
3. Edit the respective point details.
4. You can also access the point details page by
   1. On the Trend detail page, go to the **Points** tab.
   2. Click the **Equipment name** to go to the relevant Equipment detail page.
   3. Go to the **Points** tab and click on the required point name to open the relevant detail page.

#### Delete Points from Trend Group

1. Go to the Trend Group detail page. Click the **Points** tab.
2. Click the ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAbCAIAAAAPqBNFAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsYBbEG/PAAAAmNJREFUSEu1ll1P01AYx3vO6enLKDDKNhAQvNI5jHgBoiYk3PkJTExMjBd+JhMTL/wMXnrljaCJmqjZIjcKqOBgm4ORde1pezylpSvrC93AXixtz/P8nn//e84LqP4uczGXpenWbs2uNqmm2x2DMy2oyBRBlBtFUzl+bDgukb0HkVzz4MisbNnVRlLmkIxKc8J0PjImxKVU+/Ld/rEDEpCBIaCO4MWrfEbuCYfBZ0pI++1XmhrKcmnjUH/z2ag3Y7nUsrS1Mlc7SCe0GwUMQt5VzL+tYGLXh86nDXt7LxIqqOrUwwfu0PaLl7ahh8OoJEqrt5AkuEMel+zWyftKMJpXlJnHj5K199SAM3lpseimHPtLKals9vv54Xjr177vhqNX/7lnfdw4P9chTKqZO/OeD531ckSrAiDkcsnFjFqNfWswhkIo3b+NROzobb9a42yrt1EEcfbpk778dYP5pSKbLMf+hqDn8YQetk/+t3gM1Y3NZ8+tVsu9Yb/+m7gkqnXO5g4g3CaOpafm8QCUcArE6L9wgSx5XNYcF6LUhcDRIY/L1umL4jKJqJA94U6f0f/pq6J8FvI8i3fmhbNCvv7A6UYwHw40L/DdeTyhenoBQrg0l15UXCQsjLlQT697p62XaeKGllyYClhcXfA3pG4niEvXuOHMgKoBwMvF4C7X5TK/xXs3QFbpF00xwsslYdxpA/861blIFqWVm/ByIT0aKLK0soAnPVv9xOjzA/nTML9t0eZRQgFmKH99VrxyiQMRZ4JorotjpxNrp27vNykxuZaz+nGiAETMjY/wE2pYY1DEP+Td+jjtNYxiAAAAAElFTkSuQmCC) icon on the right hand of the same row of the **Point** that you want to delete.
3. A message box appears to confirm the deletion of **Point.** Click **OK** to confirm deletion of the **Point.** Click **Cancel** to abort the operation.

### Edit a Trend Group

1. On the Trend Groups search page, search for the required **Trend Group**.
2. Click the required **Trend Group** name that you want to edit. Trend details page will open.
3. In the **Details** tab, hover over the **Details** section and click the **Edit** ![](<.gitbook/assets/Screenshot 2024-06-07 132020 (3).png>)icon that appears.
4. Edit the **Trend Group** **Name**, **Location** and **Trend Report Name** as required.
5. Click **Save**. Click **Cancel** to discard the changes.

### Delete a Trend Group

1. On the Trend Groups search page, search for the **Trend Group**. Click the required **Trend Group** name to go to the Trend detail page.
2. Click the respective **Delete this Trend Group** link or **Delete** icon![](<.gitbook/assets/Screenshot\_11 (4).png>) in the Sidebar.
3. A message box to confirm deletion appears. Click **Delete** to confirm deletion of the **Trend Group,** or to close the message box without deleting, click![](<.gitbook/assets/Screenshot\_10 (4).png>) . If the **Trend** **Group** is in use, you will not be allowed to delete it.

### View Trends of Trend Group

1. Go to ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) **Settings** and click **Trend Groups** under **View** section.
2. Or go to **App Dashboard**🡪**Trend Groups** tab.
3. On the Trend Groups search page, search for the required **Trend Group** and go to its detail page. Trends associated with the configured points will be displayed.
4. **Trends** can be filtered by time range.
   1. Click the **Filter** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABUAAAAPCAIAAACEOBM8AAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwQAADsIBk7w4LgAAALlJREFUOE9j/PTpBQMFgBGk//fb87t3XHlLojHC2p6usmD9QPDt6uKayYc+EW0En21+fbQO/1smqA4u7diWXDs+4vRDNYMUw/QDmUQagaQZVT8xRqBqxtCP3wgMzdj04zICm2Yc+iFGJFkiB6asp4cOP5bQRQo/NFlWFmIiA7d+YnSjxB9xGlBVCZNv/+3bt1NTMojTz8LJx4XuPFVV1dlzZsDSP6bj766vWPfW3spOW11GUoSLFYfvAC9/OXlLeP1XAAAAAElFTkSuQmCC) icon on the top right corner.
   2. Under **From Date Time,** click **Calendar** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABUAAAATCAIAAADwLNHcAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwQAADsEBuJFr7QAAAJZJREFUOE9jtDSyYaAAMGHqPXb2MFYDsYpj0U+SaxiR3Y/LZjQTrYxt4SKU2k+pfhT3k+RziGKS/f/yxctA7xC4TSzIdn75/MXNwRMiAgxLeDghs9dvXYOshar+Jyb+SHY/NzfP7kPb4X4ZZO6navipa6gTTEJ/fv++e/ceXBml6Y+JiZF8LwD1MjEzMzMxkWMEUBdQLwCo/zyjXAZcVQAAAABJRU5ErkJggg==)icon and select the **From Date** that you want to start plotting data.
   3. Click the **Time** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAdCAIAAAA2M5tmAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsUBkTUP4gAAAxZJREFUSEu9lf9PEnEYx5Gbt7u8cfMCYaDGCWoySq3luuHKWrbZF13/aG1uzrWmrdJBP7isGATBMAgmHh0BHxQPyY67z+fuOCB0ZZ/xA/fc87zu/Xme5/N8+u7M3TP969XXA9pvsTq8DGHCGQoXADABIZMu1Gp/ltENSljH57lpB0NiHeIbopCJBUO7hfqvjvQOULM98HjBy+A9kyIK4a21D5l2MHbFxeqizdbZlWXOSen0NUTwY1/4WQGVCjg+JQnCbIYBGDnETjnxdCJ33CpAr1QiLi/6aVUiyEaC73dz1XpLiHnQOTXH3XBQyCoKsVdroYLOSafUvvCEsxPwHUhsrL78tFdpz9pprcIno3FADY9KBZQWRlqdJB/NVlSsCnUHlqbt/Yr9KLb+PJgXkdOI/z53nfWOsd5Lh8mDqmw+KWZiPOnxWOV94ZdHqHwkUz1VQmB+iKszXlKxNPZD0mb02addLgf8DegzkQut7+w3FAvunZ2BkhB00DdBQ/dSKvhVEXOGVQsHowD62dhrFvhXVjowOYqYfHynfAaa6lIOp3j4QI16BnXbtzOazmSP02L8Yj2iUmmrS4NaGNQeYklo7Z8ziK4JZVRSilYS0Nw+pra62FBL3hHnuPXIg5pOdRAbsFgqqQnVjDjW6XCmEln0Ldw2v2Lk4pooSGpCywKqIE4zal9oUqvJzdWtrlyCsSAloKQUWa5+XihBBM22b6/5qju338faYHCpkNVVvxpLI6pt4ibqNkNWW7kiKMltYvGrTJBOFnVQUzES17Ry4y3nRsdGXJBae/G2OUEIPzeFOodPfUYdDs/+SaFGTbjlhJqpYZbMRb8fwoPcKrheTIU/fvl22LQ6bz+dd8NmEBPbG3uGs28y7W2/Sx9BADm59Czg7KZXdiI8geXFSaQSxN9s57VxoRt91XQec7uHCLlrcWbM57XipQPeOP2keeq7+/CBz4EaVpqnm6+jsna4DNeJcU5LXtLkF3igNCpO2Rhaa0vJ0j6hJeOF3FH/6zZtKTe695Hxr+59Q+ef7xFdt+eL6uF9IdDfCqNMwzB+bu8AAAAASUVORK5CYII=) icon and select the **Start Time** to plot data.
   4. Under **To Date Time**, click **Calendar** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABUAAAATCAIAAADwLNHcAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwQAADsEBuJFr7QAAAJZJREFUOE9jtDSyYaAAMGHqPXb2MFYDsYpj0U+SaxiR3Y/LZjQTrYxt4SKU2k+pfhT3k+RziGKS/f/yxctA7xC4TSzIdn75/MXNwRMiAgxLeDghs9dvXYOshar+Jyb+SHY/NzfP7kPb4X4ZZO6navipa6gTTEJ/fv++e/ceXBml6Y+JiZF8LwD1MjEzMzMxkWMEUBdQLwCo/zyjXAZcVQAAAABJRU5ErkJggg==) icon and select the **To Date** that you want to stop plotting data.
   5. Click the **Time** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAdCAIAAAA2M5tmAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsUBkTUP4gAAAxZJREFUSEu9lf9PEnEYx5Gbt7u8cfMCYaDGCWoySq3luuHKWrbZF13/aG1uzrWmrdJBP7isGATBMAgmHh0BHxQPyY67z+fuOCB0ZZ/xA/fc87zu/Xme5/N8+u7M3TP969XXA9pvsTq8DGHCGQoXADABIZMu1Gp/ltENSljH57lpB0NiHeIbopCJBUO7hfqvjvQOULM98HjBy+A9kyIK4a21D5l2MHbFxeqizdbZlWXOSen0NUTwY1/4WQGVCjg+JQnCbIYBGDnETjnxdCJ33CpAr1QiLi/6aVUiyEaC73dz1XpLiHnQOTXH3XBQyCoKsVdroYLOSafUvvCEsxPwHUhsrL78tFdpz9pprcIno3FADY9KBZQWRlqdJB/NVlSsCnUHlqbt/Yr9KLb+PJgXkdOI/z53nfWOsd5Lh8mDqmw+KWZiPOnxWOV94ZdHqHwkUz1VQmB+iKszXlKxNPZD0mb02addLgf8DegzkQut7+w3FAvunZ2BkhB00DdBQ/dSKvhVEXOGVQsHowD62dhrFvhXVjowOYqYfHynfAaa6lIOp3j4QI16BnXbtzOazmSP02L8Yj2iUmmrS4NaGNQeYklo7Z8ziK4JZVRSilYS0Nw+pra62FBL3hHnuPXIg5pOdRAbsFgqqQnVjDjW6XCmEln0Ldw2v2Lk4pooSGpCywKqIE4zal9oUqvJzdWtrlyCsSAloKQUWa5+XihBBM22b6/5qju338faYHCpkNVVvxpLI6pt4ibqNkNWW7kiKMltYvGrTJBOFnVQUzES17Ry4y3nRsdGXJBae/G2OUEIPzeFOodPfUYdDs/+SaFGTbjlhJqpYZbMRb8fwoPcKrheTIU/fvl22LQ6bz+dd8NmEBPbG3uGs28y7W2/Sx9BADm59Czg7KZXdiI8geXFSaQSxN9s57VxoRt91XQec7uHCLlrcWbM57XipQPeOP2keeq7+/CBz4EaVpqnm6+jsna4DNeJcU5LXtLkF3igNCpO2Rhaa0vJ0j6hJeOF3FH/6zZtKTe695Hxr+59Q+ef7xFdt+eL6uF9IdDfCqNMwzB+bu8AAAAASUVORK5CYII=) icon and select the **To Time**, which denotes the end time to stop plotting data.
5. Click **Apply Filter for Graph**. Trends will be filtered according to the selected time range and will be displayed in the graph.
6. **Generate Report**: This is used to create a report based on the filtered trends.
   1. After applying the required time range, select the Format.
   2. Click **Generate Report.**

{% hint style="success" %}
_Tip – You can view respective_ _**User Activities**_ _associated with a_ _**Trend Group (on the respective Trend Group detail page)**_ _such as Trend Group creation, Point addition, Point Deletion, etc. on the right pane in the respective Trend Group detail page under_ _**Activities**_ _section._
{% endhint %}

### Real-Time Trends of Trend Groups

You can view Real-Time trends on a full view or on a Pop-up window.

1. Go to ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==)**Settings** and click **Trend Groups** under **View** section.
2. Or go to **App Dashboard** 🡪**Trend Groups** tab.
3. Full View: On the Trend Groups search page, click the ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABkAAAAZCAIAAABLixI0AAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsYB6tXNkgAAAjFJREFUSEtjfPXqOQOVABOVzAEZM2oWaYHJCI9HTU2dt2/fkqRbTEz0ypVLcC0Is8TEJDs62kxNTYg07tSp07W19c+ePYarZ0HWaWFhoaWlicusM2fOxMYm5OXlZGZmANX8/v0HTSWxaeL379+RkTFbt266cOHiuXPnsdqH3azPnz9PnTrt1atXcD2fPn3+/v17fX3juXPnhIWFiDXr79+/06fPaGxsXr16DUTPmzdv4+MTwsPDbG1tlixZLC8vT9isN2/evHjxorm5Zfv2nX19PTNmzDp69NizZ888PDx9fHx6erp8fX3+/ft348ZNoOlYjAOmCQiCyzk5OUJENm5cDxRkZGRcunQxkJuamgJXw8TEFBYWysLCAtcOZKDE465dOzQ01IEqIHrMzExdXJwFBQWdnZ1aW9uXLl22aNECXV2d//8ZtmzZ2tTUDLQG2XUoYc/Ozs7BwQE3i5mZedmyJVOnTga6Yv78BdnZmR4e7l1dPY8ePUpLSwH6F82bKO66f/8+A8N/zIAAhtGXL18iIyOBUsDI3blzJzBO/fx8N27chKwYke41NLSBiQhXQv327Rsw7KOjoxYuXHT48BEZGekfP35u3brt8uULWPIQ/qyTn1+4ffuOkyePAYMPqPLEiZMhIWEVFWU5Odkkm/Xu3TugcXv37gMmLmACfPLkSVRUZFNTAxcXF8lmATX8+fPn+PHjN27cYmFh1tfXMzQ0RItHRHjh9yMxssTm7aFsFgA0DQk3/GoTcQAAAABJRU5ErkJggg==) **Full View** icon to go to the Real-Time Trends Full page view.
4. Real-Time Trend Pop-up window:
   1. On the Trend Groups search page, click the required **Trend Group** name to go to its detail view.
   2. Click the **Real-Time Trends** link on the top right corner to go to the pop-up window of the Trend Group’s Real-Time Trends.

### Dynamic Trend Groups

You can create Trend Groups which are dynamic and which will be used only for the required period to view trends. Configured Dynamic Trend Groups will not be saved in the database and will be only used until you view their live trends.

To configure a Dynamic Trend Group;

1. Go to **Settings** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==)🡪Configure🡪 Trend Groups.
2. On the Trend Groups search page, click the **Create New Dynamic Trend Group** link on the top right corner.
3. Select the **Location** that you are interested in to filter the **Equipment** based on the selected Location and click **Create**. Dynamic Trend Groups page will be opened.
4. Click the **Add** ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAdCAIAAAAyxktbAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsUBWmncRwAAAfhJREFUSEu1lllPg1AQhXvZGkNBW6lafTEucYkm/v9fYaKpGpf0ydZQaGWJadk8CF4LBUKhNn0AMvPNYe5cziWGMWr8z48UoH3ft23bNKzZbO55nuu4HM+xLNtsCpLcEkWRYZgCVdlogMaqPplMG0GQm0xIu72ldDsolhmTgTYMczT88D2/TJ8IQ3r7e7IsLQen0aqqaapWBroYs610ujtKKivRrGpcELWxjtxctGmaFfRSHHLRyUV6rNp13eH7x6p9SMVjhcChD2O0rk2K1+3s/Pry6gZ/wmTPA4gggJNAY351fVpTcpQODmjRdajasuyi+V2pZhCYprWA/r1ZCZIXbEMoVf31NVsLNIJQWrhlnh6fAz+xobFWF5fXZeo99O8C31uMxP48Oz+Ne53iliEWxFBauIyoUxOXSCcxLWzI68vAmc+L6Zhrlgsnun9/WxzJC8LxyWHckI2N5hpVU1rYELElrhFNaSFaklqN3wbVrUFISKNzDR+CX9SF/uSDQ10ttgJ8sd5eByWdJU8EwzJHx4ccx/2pxhXu93q7NYWDQLnxhERE+Bt8qDIduSmHTBgY/K2z3a5AR9ayN2Y7+vB9VHb3E7J/UM7RI8mO44zH+ufUKD6HbG7JitLheT7zRcuenjBCnuthr2OhBIGXN6WKp6cK7V5O+QaIDOrF/icMDwAAAABJRU5ErkJggg==) icon on the top right corner.
5. Select the required **Equipment.** Points of the selected Equipment will be displayed.
6. Select the **Data Type** and the **Unit** as required to filter the Points further.
7. To view only the trend enabled points, select the ‘Only Trend enable points’ checkbox.
8. Click ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAaCAIAAADJ6rCnAAAAAXNSR0IArs4c6QAAANtJREFUSEtj/PTpBQNVARNVTQMZNhRMZPy2dyLb6Y9U8Ltp+DdTfpA5nz49+NVg9J+BgRL0r2Hr108vgJEMimcwRZGhyMYBTYPEDMePonW/G4zI8Pv/hq3fi4z/IumExzU5hmIah5Z6SDMUq3GY6ZFYQ3EZhzWFEzYUj3G48gw+Q/EbhycXgg1Nwoj8pGVoMYuZPPDkaw4GOQz1cvzICQVrahsKJcWoG8koKLBoISYcZf97x/2dPv/3mUvfiowJWsuIpy5kuXWMhUHlt5oYwTSIbA0+Ewk6Z8imcABigqIXr0x+TQAAAABJRU5ErkJggg==) icon to select the required Date/Time range to select the Trend period.

## Data Sources

**Data Sources** allow you to configure custom points, which can be used to show user required custom data as point values on IBMS dashboards. A **Data source** is configured using a custom **Data Source script** written in different data protocols such as SQL, Python.

The following on **Data Sources** are described below.

1. [Configure a Data Source](chapter-3-configuration-of-prerequisites.md#configure-a-data-source)
2. [Edit a Data Source](chapter-3-configuration-of-prerequisites.md#edit-a-data-source)
3. [Delete a Data Source](chapter-3-configuration-of-prerequisites.md#delete-a-data-source)

<mark style="color:blue;">**Path**</mark>\
<mark style="color:blue;">**Settings icon**</mark>![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) <mark style="color:blue;">**🡪**</mark> <mark style="color:blue;">**Configure**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section🡪</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Data Sources**</mark>

### Configure a Data Source

This describes how to configure a custom point using **Data Source script** written in a data protocol.

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Data Sources** under **Configure** section. **Search Data Source** page will appear.
2. Click **New Data Source** link on the top right corner. New Data Source configuration page will appear.
3. In the **Point Name** box, type the name of the custom point that you want to configure.
4. In the **Data Type** list box, select the relevant **Data Type**.
5. In the **Units** box, type the Unit of the point. e.g. ‘C’ if the point is to denote temperature.
6. In the **Data Protocol** list box, select the data protocol used to write the **Data** **Source script**.
7. In the **Data Source Script** box, write the **Data Source script** to get the required point.
8. Click **Create**. A new Data Source will be created and listed under **Data Source** search page.

### Edit a Data Source

This describes how to edit the configuration details of a selected **Data Source**.

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Data Sources** under **Configure** section. **Search Data Source** page will appear.
2. In the **Search Data Sources** box, type the name of the **Data Source** or part of the name that you want. Matching data will be listed.
3. Click the **Point Name** to go to the detail page of the **Data Source**.
4. Hover over the **Data Source Details** area and click the **Edit** icon to go to the edit mode.
5. Edit the details accordingly and click **Save**.

### Delete a Data Source

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Data Sources** under **Configure** section. **Search Data Source** page will appear.
2. In the **Search Data Sources** box, type the name of the **Data Source** or part of the name that you want. Matching data will be listed.
3. Click the **Point Name** to go to the detail page of the **Data Source**.
4. Click the **Delete** icon ![](<.gitbook/assets/Screenshot\_11 (4).png>)or **Delete this Data Source** link. A message appears to confirm the deletion.
5. Click **Delete**. Click ![](<.gitbook/assets/Screenshot\_10 (4).png>) to abort the operation.

## Real-Time Reports Configuration

For details on Real-Time Reports, go to the section [Real-Time Reports.](chapter-8-reports.md#real-time-reports)

## Escalated Alarm Message Templates

\
IBMS Message Templates are used to configure E-mail, HTML e-mail (Rich-text) and SMS templates that need to be sent especially in escalated Alarm messages.\
This section describes the following:

1. Create a New Escalated Alarm Message Template
2. Edit a Message Template
3. Delete a Message Template
4. Export a Message Template



**Path**\
**Settings** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==)on the Application Dashboard 🡪 **Configure** section 🡪 **Escalated Alarm** **Message Templates 🡪 Escalated Alarm Message Templates** search page

_<mark style="color:blue;">Setting under App Configuration</mark>_\
_<mark style="color:blue;">**Escalated Alarm Message Templates**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">configured here (Settings🡪Configure🡪Escalated Alarm Message Templates) will be populated in “</mark><mark style="color:blue;">**Assignee Message Template**</mark><mark style="color:blue;">” and “</mark><mark style="color:blue;">**Un-assignee Message Template**</mark><mark style="color:blue;">” Drop down boxes in</mark>_ _<mark style="color:blue;">**App Configuration page**</mark><mark style="color:blue;">, which enable user to select accordingly.</mark>_

### Create a New Escalated Alarm Message Template

To configure an Escalated Alarm Message Template;

1. On the Escalated Alarm Message Templates Search page, click the **Add** **New Message Template** link. New Escalated Alarm Message Template configuration page will appear.
2. In the **Name** box, type a name for the new message template.
3. In the **Subject** box, type the subject of the message.

#### Configure Plain Text Message Template (plain text e-mail)

1.  In the **Message** box, configure the message using message text and relevant **Placeholders.**



    Note –The default message that created here is the plain text e-mail message. Once you have created the Message Template, you will have the ability to create other templates.
2. Select the **From Address**.
3. Add Recipients.
   1. Click the **Add Recipient** link.
   2. Click the **Info** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAdCAIAAAA2M5tmAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsUBkTUP4gAAAnBJREFUSEutll2P0kAUhrfTD5aPQqEFWdyP4I2bTbwwJsZL/4GJP9UL/4DJZuONF2s26g2RrAtuC5RCQeiHvmUQWOhMK3EuSpN536dnzmHOjPCpe33wv4fAgoZhOHUn7sidz7wwDPy5LykSIaKSkfNqPpvPEUJYwcRAgyCwrYFjj36HIdNGSFFTNaMsiuKuZhs6dkbWz17oB2lSQkRi1I1CUd0SP1hC3xrc/7hPSQQoDELo+2afCQXR3plOEy9yBe+mchmpOxrvR6QseJG3FTeC+r5vdi1+UC/On799/QZPlgyVAIfORlCnP+TnsVo2zuqnUOKpqaVYLgjgLKH4Pw4HDj/M8a/JSjDzPZYYHNAwK3z4dokKJhYkm80166etbns6XX9g11Vt1NSSSiZjngg2WZaxfLzctL7widBgE0aRvrt8783mrEhfPXvZ0I/o7F2vc3X9kb8mOaOcPDkhwd+SxarvrO7V5yUIdFaVVl5KI9gVnI+3O21zuP63capEIZSGvsNsNlRXLUUJxfB8LzGnwqJ1EVGS+GkyFlWKcmp1+ErMSnJEI5lDhS9t6HUqMIe9RCilEbRbvjR3uBSYdsJWBofSCNo4TQRrIJV06uLs6UXzHLuApQQHtAiKgR7Ogd58/0q5DeMom8lyagUOPWOizo/uctu6Td+bYyMgknjcPJYWZY/AeDMe6YlF4AtAoMQlFD84Z3CK7c2Fd/OkWpeoUq1ourYHFy54N40P6l6p6bXHtcQ9tvKj3NDDtRVKzLnved7Asl1nzDn3DwShUFLLhobGuLu4VDcUXC8CzxdlCVcHWZEKxcI/31D2SOuW5Q95LhHUjesAJwAAAABJRU5ErkJggg==) and select the relevant recipient from the window that appears.
4. To add multiple recipients, repeat the step 6.
5. To remove a recipient which is already added, click the respective **Delete** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAbCAIAAAAPqBNFAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsYBbEG/PAAAAmNJREFUSEu1ll1P01AYx3vO6enLKDDKNhAQvNI5jHgBoiYk3PkJTExMjBd+JhMTL/wMXnrljaCJmqjZIjcKqOBgm4ORde1pezylpSvrC93AXixtz/P8nn//e84LqP4uczGXpenWbs2uNqmm2x2DMy2oyBRBlBtFUzl+bDgukb0HkVzz4MisbNnVRlLmkIxKc8J0PjImxKVU+/Ld/rEDEpCBIaCO4MWrfEbuCYfBZ0pI++1XmhrKcmnjUH/z2ag3Y7nUsrS1Mlc7SCe0GwUMQt5VzL+tYGLXh86nDXt7LxIqqOrUwwfu0PaLl7ahh8OoJEqrt5AkuEMel+zWyftKMJpXlJnHj5K199SAM3lpseimHPtLKals9vv54Xjr177vhqNX/7lnfdw4P9chTKqZO/OeD531ckSrAiDkcsnFjFqNfWswhkIo3b+NROzobb9a42yrt1EEcfbpk778dYP5pSKbLMf+hqDn8YQetk/+t3gM1Y3NZ8+tVsu9Yb/+m7gkqnXO5g4g3CaOpafm8QCUcArE6L9wgSx5XNYcF6LUhcDRIY/L1umL4jKJqJA94U6f0f/pq6J8FvI8i3fmhbNCvv7A6UYwHw40L/DdeTyhenoBQrg0l15UXCQsjLlQT697p62XaeKGllyYClhcXfA3pG4niEvXuOHMgKoBwMvF4C7X5TK/xXs3QFbpF00xwsslYdxpA/861blIFqWVm/ByIT0aKLK0soAnPVv9xOjzA/nTML9t0eZRQgFmKH99VrxyiQMRZ4JorotjpxNrp27vNykxuZaz+nGiAETMjY/wE2pYY1DEP+Td+jjtNYxiAAAAAElFTkSuQmCC).
6. Add recipients under **CC List** and **BCC List**.
7. Click **Create** to create the new message template. Detailed page of the created Message template will appear. Observe that there are 5 tabs, **Notification Template, Message, Rich Message, Short Message** and **Attachments.**

| Placeholder                                  | Description                                                            |
| -------------------------------------------- | ---------------------------------------------------------------------- |
| AlarmDateTime                                | This is the time stamp of alarm occurrence.                            |
| ClearedDateTime                              | Alarm cleared Date Time                                                |
| AckedDateTime                                | Alarm Acknowledged Date Time                                           |
| AlarmMessage                                 | Returns the alarm message                                              |
| All\_Alarm\_Assignees                        | Returns the users assign to the alarm                                  |
| Alarm\_Assignee\_comment                     | Returns the assignee comment which is given when adding a new Assignee |
| Alarm\_Assignee                              | Returns the Assignee                                                   |
| Alarm\_Unassigned                            | Returns the Unassignee                                                 |
| AssignedBy                                   | Returns the Assigned By User                                           |
| UnassignedBy                                 | Returns the User who unassigned                                        |
| AlarmPriority                                | Returns the alarm class                                                |
| OperatorNote                                 | Returns the operator note                                              |
| PointValue                                   | Returns the Point Value of the alarmed point                           |
| PointName                                    | Returns the point name                                                 |
| PointDescription                             | Returns the Point Description                                          |
| AssetName                                    | Returns the Asset Name                                                 |
| AssetLocation                                | Returns the Asset Location                                             |
| AlarmSeverity                                | Returns the Alarm Severity Key                                         |
| AlarmSeverityName                            | Returns the name of the Alarm Severity                                 |
| AlarmClass                                   | Returns the Alarm Class                                                |
| AlarmLocation                                | Returns the Alarm Location                                             |
| ExpireTime\_EscalationLevel\_1               | Returns the expiration time of alarm escalation level 1                |
| ExpireTime\_EscalationLevel\_2               | Returns the expiration time of alarm escalation level 2                |
| ExpireTime\_EscalationLevel\_3               | Returns the expiration time of alarm escalation level 3                |
| ExpireTime\_EscalationLevel\_4               | Returns the expiration time of alarm escalation level 4                |
| ExpireTime\_EscalationLevel\_5               | Returns the expiration time of alarm escalation level 5                |
| ExpireTime\_EscalationLevel\_1\_After\_Hours | Returns the after hour expire time of alarm escalation level 1         |
| ExpireTime\_EscalationLevel\_2\_AfterHours   | Returns the after hour expire time of alarm escalation level 2         |
| ExpireTime\_EscalationLevel\_3\_AfterHours   | Returns the after hour expire time of alarm escalation level 3         |
| ExpireTime\_EscalationLevel\_4\_AfterHours   | Returns the the after hour expire time of alarm escalation level 4     |
| ExpireTime\_EscalationLevel\_5\_AfterHours   | Returns the the after hour expire time of alarm escalation level 5     |
| SMSAlarmAckCode                              | Returns the SMS Alarm Acknowledge Code                                 |
| AckedUser                                    | Acknowledged User                                                      |
| AckedTime                                    | Acknowledged Time                                                      |
| AlarmPageLink                                | Returns the Alarm Page Link                                            |
| Name                                         | Returns the full name of the recipient                                 |
| Type                                         | Returns the type of the recipient. This is usually the 'User'          |
| Key                                          | Returns the Key associated with the recipient in the System            |

#### Configure Rich Text Message Template (HTML e-mail)

Rich Text Message Template allows you to configure a message template for HTML e-mail messages. A Rich Text Message can contain tables, different fonts, HTML formatting and styles. If you know HTML coding, you can go to the code level and make changes to format your template.

1. On the Message Template detailed page, click the **Rich Message** tab.
2. In the text box, use given tools and **Placeholders** (Click the **Show Placeholders** link to bring up **Placeholders** list and select from it) to format your message template.
3. Click the **Apply Template** button to select a format out of preset template formats.
4. Click on **\</>** link to switch between code editor and form editor modes.
5. Once you are done formatting the message, click the **Update** button to save the template or **Cancel** button to discard all your changes.

#### Configure Short Message Template

A short Message Template is meant for the messages to be sent to mobile devices, (e.g. SMS).

1. On the Message Template detailed page, click the **Short Message** tab.
2. In the given box, configure the short message using message text and relevant **Placeholders.**
3. Click **Update.**

#### Add Attachments to Message Template

You can attach attachments related to the Message to be sent.

1. On the Message Template detailed page, click **Attachments** tab.
2. Click the **Add** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAdCAIAAAAyxktbAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsUBWmncRwAAAfhJREFUSEu1lllPg1AQhXvZGkNBW6lafTEucYkm/v9fYaKpGpf0ydZQaGWJadk8CF4LBUKhNn0AMvPNYe5cziWGMWr8z48UoH3ft23bNKzZbO55nuu4HM+xLNtsCpLcEkWRYZgCVdlogMaqPplMG0GQm0xIu72ldDsolhmTgTYMczT88D2/TJ8IQ3r7e7IsLQen0aqqaapWBroYs610ujtKKivRrGpcELWxjtxctGmaFfRSHHLRyUV6rNp13eH7x6p9SMVjhcChD2O0rk2K1+3s/Pry6gZ/wmTPA4gggJNAY351fVpTcpQODmjRdajasuyi+V2pZhCYprWA/r1ZCZIXbEMoVf31NVsLNIJQWrhlnh6fAz+xobFWF5fXZeo99O8C31uMxP48Oz+Ne53iliEWxFBauIyoUxOXSCcxLWzI68vAmc+L6Zhrlgsnun9/WxzJC8LxyWHckI2N5hpVU1rYELElrhFNaSFaklqN3wbVrUFISKNzDR+CX9SF/uSDQ10ttgJ8sd5eByWdJU8EwzJHx4ccx/2pxhXu93q7NYWDQLnxhERE+Bt8qDIduSmHTBgY/K2z3a5AR9ayN2Y7+vB9VHb3E7J/UM7RI8mO44zH+ufUKD6HbG7JitLheT7zRcuenjBCnuthr2OhBIGXN6WKp6cK7V5O+QaIDOrF/icMDwAAAABJRU5ErkJggg==).
3. In the **Name** box, type a name for the attachment.
4. In the **Type** box, select ‘**File (Attach a File)**’ option.
5. Select other **Options**.
6. Drag and drop the required file to be attached to the Message Template or click the marked area to select a file from the file explorer.
7. Click **Upload**.

### Edit Message Templates

1. On the **Escalated Alarm** **Message Templates** search page, select the Message template you want to edit and click on it to go to its detail page (inside Notification Template tab).
2. Edit the message template as you want. (See above).
3. Click **Update**.

### Delete a Message Template

1. On the **Escalated Alarm** **Message Templates** search page, select the Message template you want to delete and click on it to go to its detail page.
2. Click the **Delete this Template** link or click the **Delete** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAbCAIAAAAPqBNFAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxQAADsYBbEG/PAAAAmNJREFUSEu1ll1P01AYx3vO6enLKDDKNhAQvNI5jHgBoiYk3PkJTExMjBd+JhMTL/wMXnrljaCJmqjZIjcKqOBgm4ORde1pezylpSvrC93AXixtz/P8nn//e84LqP4uczGXpenWbs2uNqmm2x2DMy2oyBRBlBtFUzl+bDgukb0HkVzz4MisbNnVRlLmkIxKc8J0PjImxKVU+/Ld/rEDEpCBIaCO4MWrfEbuCYfBZ0pI++1XmhrKcmnjUH/z2ag3Y7nUsrS1Mlc7SCe0GwUMQt5VzL+tYGLXh86nDXt7LxIqqOrUwwfu0PaLl7ahh8OoJEqrt5AkuEMel+zWyftKMJpXlJnHj5K199SAM3lpseimHPtLKals9vv54Xjr177vhqNX/7lnfdw4P9chTKqZO/OeD531ckSrAiDkcsnFjFqNfWswhkIo3b+NROzobb9a42yrt1EEcfbpk778dYP5pSKbLMf+hqDn8YQetk/+t3gM1Y3NZ8+tVsu9Yb/+m7gkqnXO5g4g3CaOpafm8QCUcArE6L9wgSx5XNYcF6LUhcDRIY/L1umL4jKJqJA94U6f0f/pq6J8FvI8i3fmhbNCvv7A6UYwHw40L/DdeTyhenoBQrg0l15UXCQsjLlQT697p62XaeKGllyYClhcXfA3pG4niEvXuOHMgKoBwMvF4C7X5TK/xXs3QFbpF00xwsslYdxpA/861blIFqWVm/ByIT0aKLK0soAnPVv9xOjzA/nTML9t0eZRQgFmKH99VrxyiQMRZ4JorotjpxNrp27vNykxuZaz+nGiAETMjY/wE2pYY1DEP+Td+jjtNYxiAAAAAElFTkSuQmCC) on the side bar on the right.
3. A message to confirm the deletion appears. Click **Delete**.

### Export a Message Template

To export a Message Template;

1. On the **Escalated Alarm** **Message Templates** search page, select the Message template you want to export and click on it to go to its detailed page.
2. Click **Export** link ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAaCAIAAAA44esqAAAAAXNSR0IArs4c6QAAActJREFUOE9jfPX8FQO5gIlcjSB9I1EzI67Qvre5bvZ5YKAYp9b5K+EIVZwB9vv7u7fvgOjTN9zxMWhC+9ubl2+/ff8GRJ++Q5z7+/snEPfbuxdvoCIIb6AH2Lenuyb2b7r/B82jLDL22SWBqlyowuh+5pJ2yy/0U2RBVoVdJ3ry/P3u9sE9F7+h6Ifq/HZ518E7b3+j2gx29u+3N09tW7fl7P3vIOeyaCS2Zxizgty/7bc1yLW/z82qW3QJ7GUWGbPgcA8LdSFWIIfx9sbqymW3wZrEta0dPKws1MVBEuDA+vablQvKAVmwf8fBI1dfgcNDPry70Jbl9+/fIJ6YeWZyhCFcG0QzXCeILaxuHaJuZnN+9ezpp14y/PkD9AIsZF6dnN5+kkVI097ZzdlMVQRmN8yPv9/cObF3z4GDN14ixwNKsP55d33vaiBi4ZQ3DvL1slIRZnh3+9iObZvP3f6EHnkgY5H8jDsNY8qwyIc3FdpiCW18hrBwKhr5BTlDAxUlhQHj+diOjevOPQBHGUo6AXvE1UpFAjk0sOZnUPBs3rzp9MPvDJwKpj7+HmaqkuhBCPYzvqIXGI2srNh0QR2FNz/j1Qk0gKLCAACfStoYknNA3QAAAABJRU5ErkJggg==) on the Side bar.
3. Save the attachment.

## Alarm Escalation Disable Message Templates

**Path**\
**Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAYCAIAAABm/grVAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwwAADsQBiC4+owAAALRJREFUSEvFVUEOgCAME9+qiU8y0Qd69gWSYMgscx0kIicCXelWBuE8j4GNeVoyZNtXBh9GFSFZ5DyCja1MpZCmMOAqzzZgAdKnXGpmUJOH0jbGMq0HqceEaqXUVicAjWoQW4boV8qp6A12u29bJLV4kFwpZOepDydtKMVPpEbvE6Pkdm1fdbpSWNNamep79r1RDTKTGRDY5ZWSVsa52j+w7nI/gWg7GjD8Tug/SA+LDJ+4fwHNY1PGX6HgqAAAAABJRU5ErkJggg==) on the Application Dashboard 🡪 **Configure** section 🡪 **Alarm Escalation Disable Message Templates 🡪 Escalation Disable Message Templates** search page\
\
To configure an Alarm Escalation Disable Message Template;

1. On the Escalation Disable Message Templates search page, click the **Add** **New Message Template** link. New Point Message Template configuration page will appear.
2. Follow the relevant steps under the section named “**Create a New Escalated Alarm Message Template”** described above.

_<mark style="color:blue;">Setting under App Configuration</mark>_\
_<mark style="color:blue;">**Alarm Escalation Disable Message Templates**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">configured here (Settings🡪Configure🡪Alarm Escalation Disable Message Templates) will be populated in “</mark><mark style="color:blue;">**Alarm Escalation Disable Message Template**</mark><mark style="color:blue;">” Drop down box in</mark>_ _<mark style="color:blue;">**App Configuration page,**</mark>_ <mark style="color:blue;"></mark><mark style="color:blue;">which enables user to select a relevant message template.</mark>

## Link Templates & Links

Controls (e.g. button) on Real-Time (RT) Pages of Equipment can be linked to other RT pages or to required URLs according to your requirements, (e.g. clicking a button on a RT page, can open another RT page or can direct to another URL).

Before providing links to Controls on RT pages, you need to perform the following operations;

1. [Create **Link Templates** under **Equipment Template** ](chapter-3-configuration-of-prerequisites.md#create-link-templates-on-equipment-template)Configuration.\
   This is used to create a template for links. Created **Link Template** will be applied to the **Equipment** configured using the respective **Equipment Template.**
2. Create **Links** accordingly, for **Equipment** under respective **Equipment** configuration page. When you configure RT pages, you shall add the pre-configured **Links** to **Controls** on RT page.

### Create Link Templates on Equipment Template

To create Link Templates on an Equipment Template;

1. Click the **Settings** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAIAAACEIhGsAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxgAADsQB2OOvEAAAALNJREFUSEu9VdEOgCAIzL61tj6prT6wZ78gm5siIqCpPbk4z4MDNdY+C/vt2xHi133yYBddcwSkgGuHZEKBBzP6PYiodCoJMzBrkYhMGZUiamyjyxOKjJqq12kUTVQCEmcaZOZbiO5RainBPq95T6AKDVLQiJLSlKV/1tMZmbnmnIGx2smZ0T1JHWsFkrfUSGcaBHoD0MbBdw80zq3JCUH/Za89Qpw2Bpa8CmTTdngLf95mL07MU8bzyyrxAAAAAElFTkSuQmCC) and select **Equipment Templates** under **Configure** section. **Equipment Templates** Search page will appear.
2. Go to the detailed page of the required **Equipment Template**.
3. On the **Link Templates** tab, click the **Add** icon![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAdCAIAAABE/PnQAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOwgAADsUBWmncRwAAAf9JREFUSEu1lmlPwkAQhtlexJRWgXp/MR4BiST+/19hovGIR/wkmNKCLQ2BXr6klS6lrT204Qubmeedmd3ZWWIYw9p/fiRbwPM8y7JMYzqfL1zXdWyH4zmWZet1QZIboigyDJMdXqoAcCNVH48nNd9PRRDSbO4ouy1IptkkCxiGORx8eq6Xp3iEIYdHB7IsJRonCKiqpqlaHjRt01Zau3vKple8guXo4GojHb6/CJimWSL2FRS+qG1MI8rAcZzBx2fRysTssXPg0IuRgK6Ns3e10+33rq7xI0zqmQEBnAQBnHddn1QMP3AHB7QVKsxgOrWyznshZd83zemGALVUiJZobCHcny/MYDabV+euCDQtbLSnx2ffW7sSsJOXvX4e1Yf7W99zaUv0dqd7EayEGcToebgZNjQtFIBmReiaO4loYYleX97txSJbA33AcssOuL+7ybbkBeHs/GStRFtb9T/MgKaFJRIb4h8K0LRQQJIaNapwlcQIWdJifYDJh9lUifvjDA49R6OBg1vw7fU95xRLC4VhmdOzE47j4hngP1YPDvcrJgECTY8aLeBirmLyldaA7+Zkjo9MzNVWu1lCA16JMzn1VTH4GOa9Pwg5Oi7yqgjCt217NNK/Jkb2u2h7R1aUFs/zaUkXeNnhmLmOi9sC2ygIvLwtVXrZldiGRJdvGAPqxTaNp4oAAAAASUVORK5CYII=).
4. In the **Link Name** box, type a name for the **Link** template.
5. Click **Add**.

{% hint style="info" %}
_Note – Created_ _**Link Template**_ _will be applied to_ _**Equipment**_ _configured using the respective_ _**Equipment Template**. Under_ _**Equipment**_ _configuration, required_ _**Links**_ _can be configured according to the requirements._
{% endhint %}

### Configure Links on Equipment Configuration page

After creating **Link Templates** on **Equipment Template** configuration page, you shall configure **Links** on the **Equipment** created using the respective **Equipment Template**.\
\
To configure **Links** under **Equipment** configuration page;

1. Click **Equipment** tab on the IBMS home page or go to Settings🡪View🡪Equipment. Equipment search page will appear.
2. Search by the respective **Equipment Template** by using the **Equipment Template** filter on the Side bar.
3. Click the **Equipment** name to go to the Equipment details page.
4. Click the **Links** tab. Pre-configured Link template name/names will be displayed.
5. Click the respective **Edit** icon ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACEAAAAgCAIAAAAT2oadAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAOxAAADsIBw3GpnQAAAmxJREFUSEu9lm9zmkAQxsuBWseIpoB/cGKnk07zspPOtN//U3RSx7dN04IaQYICR/ooHTngDtBO4vDCgd3nx+6yuyf5/uObF/6RF9bfy0uVccRx7Hmes3Z3ux2lcRSGSqMhy6TVaqm9bqfTIaTiRcsYlFLbWqxWj89xLApXIuTysq8bmizLQhtRHI7j/Lr/HVNaJ5lEJmNzpKoq15gfh2XZ9h+7jjproxu6MdCLXpxUngeAtG3Z8K1muK57RgRHXfgiyTlMJo4oiu5/PpyQIkkqGqOK0GHvZxjLxapmkTVj8Pn26+2Xb+bkKoeBAnT4DPTBcpl5JgpoMBpPpx+SthiOzM5FN2cJHagdb6ZxbDabkj44OgAwmUxZUUVRcgzooK4chutsKisxGJk5AJq/WGTobFyPw/D9XTnjAMhkPwzD+fzuOeb0KauW5orSsITBBcxm34PtluvFqqWMmAqHkm4MixGUAEBl1VIGZo4oDsddIy3Hp/hfDoAlZiWnHrLc4DImV+/DIIBogqkDgJmipGoprd1ucRlqt3d9fZNgPM+tjCARYdVSxkW3I8pVV1X/Ye6ERc75smrpbEdnzn7Mi23YetsmZD+XgiCg2UEkeicU49PNx+N+ZCpz2GhFt93W95+ecNUEQAE67ALOfEua/o6IV2blFEgMoAAd1jjDwOQZm8OaWiIzKOQmWL4nsJOxMs/GwLe41Tl9h52s6doZGHhx97nw7HM4lzyUDBj2JfAhmZMTzyWJP1rashbO2inbK5LU6/cMQ2s0+GNiP1dOOidGEcUXLKOmitxsNnt99X/PiWeUhOvyGmfq12D8BfHtRsnuqWCOAAAAAElFTkSuQmCC).
6. On the **Link Details** window, type the required URL of the destination page, which will be linked using the respective **Link**.
7. Click **Update**.

{% hint style="info" %}
_Note – You can apply the pre-configured_ _**Links**_ _to the_ _**Controls**_ _on respective RT Pages._
{% endhint %}
