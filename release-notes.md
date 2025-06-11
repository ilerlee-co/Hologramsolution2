# Release notes

<details>

<summary>June / 25Y</summary>

### <mark style="background-color:blue;">(06.11)</mark> <mark style="background-color:blue;"></mark><mark style="background-color:blue;">**Update list**</mark>



<mark style="color:purple;">`SaaS Platform`</mark>&#x20;

**WhatsApp**

1. [Survey form’s internal question has changed(deleted Region, added Prefer date)](https://github.com/iCloudHospital/iCloudHospital/issues/1970) (#1970)

2) [Chat session refresh token duration was changed to 180d(from 30d)](https://github.com/iCloudHospital/iCloudHospital/issues/1979) (#1979)



`Admin`&#x20;

**Major Updates**

1. [Chat session would be opened when the manager sends a Template.](https://github.com/iCloudHospital/iCloudHospital/issues/1971) (#1971)



**Minor Updates**

1. [The initial assessment question type box was revised](https://github.com/iCloudHospital/iCloudHospital/issues/1970) (#1970)



**Fixed bugs**

1. [Admin role / CH Manager role can not access the ‘Chats’ category now. ](https://github.com/iCloudHospital/iCloudHospital/issues/1975) (#1975)
2. [Request hand off email’s URL error has been fixed.](https://github.com/iCloudHospital/iCloudHospital/issues/1976) (#1976)
3. [Chat sorting system has fixed (Recent message → Earlier message)](https://github.com/iCloudHospital/iCloudHospital/issues/1977) (#1977)



</details>



<details>

<summary>May / 25Y</summary>

### <mark style="background-color:blue;">(05.30)</mark> <mark style="background-color:blue;"></mark><mark style="background-color:blue;">**Update list**</mark>

<mark style="color:red;">`CH Platform`</mark>&#x20;

**Major updates**

1. A sticky icon button that is linked to the Enquiry form & WhatsApp would be added.
   1. **Enquiry form** -> CH Main contact channel was linked.
   2. **WhatsApp** -> CH Next was linked(It could be acknowledged in the Admin service.)





***

<mark style="color:purple;">`SaaS Platform`</mark>&#x20;

**Major updates**

1. The Patient Success Manager's own CH email was included with the local managers' role.
   1. (from Info@icloud to Grace & Anna @icloud)&#x20;



***

`Admin`

**Major updates**

1. **The patient's chat session was changed to open immediately without an automated flow form response.**
2. **A filter function will be added to the Patient list side.**
   1. **Sorting**
      1. Ascending&#x20;
      2. Dscending
   2. **Categorization**
      1. Assignee
      2. Confirmed / Not confirmed
      3. Activated / Deactivated / Expired

3) **From now on, we can identify easily confirmed / not confirmed messages via the User Interface, depending on the assignment.**
   1. **Assigned ( to a specific agent )**
      1. **Not confirmed**
         1. There are red color chips and an outline stroke.
         2. It only appears when the agent didn't check the chat session, even though the patient had already sent a message to the agent.
      2. **Confirmed**
         1. Red color chips and an outline would disappear when the assigned agent has checked the chat successfully.
   2. **Unassigned ( to all agents who belong to the hospital )**
      1. **Not confirmed**
         1. It will be exposed to the whole agents when a specific agent isn't assigned to the patient.
      2. **Confirmed**
         1. Not confirmed symbol(red chip & outline) will disappear when someone clicks the chat, which has just opened, or the latest message was from the patient.
4) **When sending the WhatsApp Push(Template message), the chat session will be linked with your patient to whom you have sent the template message.**



**Minor updates**

1. The patient status CTA button is designed prominently.



***

###

### <mark style="background-color:blue;">(05.14)</mark> <mark style="background-color:blue;"></mark><mark style="background-color:blue;">**Update list**</mark>

<mark style="color:red;">`CH Platform`</mark>&#x20;

**Major updates**

1. We've revised the enquiry form Enhancement (To follow HIPAA & GDPR Compliance).
2. The hospital recommendation sticky banner will appear on the Specialty contents.&#x20;



**Minor updates**

1. KakaoTalk contact point will be newly settled on the Footer
2. CTA buttons, which were included in the Hospital result, were reinforced.



***

<mark style="color:purple;">`SaaS Platform`</mark>&#x20;

**Minor updates**

1. The sticky icon, which is linked to the Enquiry form of the SaaS, will be added to the lower right side(Stacking structure).



***

`Admin`

**Major updates**

1. **Patients will be configured with the statuses.**
   1. **Activated**
      1. (24-hour window open status as the patient requested the consultation via WhatsApp.)
   2. **Deactivated**
      1. (When the window time exceeded, which is regulated by Meta -> in 24 hours.)



2. **The survey form button was updated next to the typing chat area.**&#x20;
   1. **Survey form**&#x20;
      1. (An automated Initial assessment to gather patient information, which is recorded on the upper left side button of the Chat session screen.)
      2.  You can check the patient's personal information securely, such as the below.

          <figure><img src=".gitbook/assets/스크린샷 2025-05-28 18.33.01.png" alt=""><figcaption></figcaption></figure>
   2. **Sign-in form**&#x20;
      1. (Needed to send for making an appointment, for patients themselves.)
   3. **Appointment form**
      1. (Some patients who finished the Sign-in via the Sign-in form can make an appointment themselves. It would also be recorded on the upper left side button on the Chat session screen.)



**Minor updates**

1. **Join & Transfer**
   1. Only an agent can join the chat session, which is opened by the patient.
   2. Someone who joined the chat could transfer it to another agent.

</details>
