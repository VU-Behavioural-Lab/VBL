# Granting or denying payment
{% if study_type == 'online' %}
While your study is running, you are responsible for updating the participation status of the registered participants. Participants will be paid out after the timeslot deadline ends. To pay out the participants, we will need to know the status of their participation.

- For participants who sign up and participate: they are marked as “participated”. This is done manually by the researcher themselves or automatically when they complete your study if it is setup through the survey website.
- For participants who sign up to participate but do not end up participating. In these cases, you should select “Excused” under “No-Show” instead. The participant will be denied payments.
- For participants who sign up and participate but their data-quality is not good enough, you can still deny payments.


>[!info] <i class="fa-solid fa-info"></i> &nbsp How to navigate to the payment page on SONA 
>
>1. In SONA, locate and click on **'My Studies'**. This will take you to a list of all your posted studies. 
>2. Among your studies, find the specific study for which you want to grant or deny payments and click on it. This action will display the study's details.
>3. Under the study details, click on **'View/Administer Time slots'**. You will see a display showing the current schedule and time slots for the study.
>3. To grant or deny payment for a specific time slot, click on **'Modify'** next to that time slot.
>4. Here, within the **'Sign-Ups' section**, you'll find a table listing the participants scheduled for that time slot.
>5. Grant or deny payment based on the instructions below.
>6. Carefully check that no students are left with the status "No action taken". You can check these in the tab **"Uncredited sign-ups"**
>7. After making your selections for each participant, scroll down to the bottom of the table and make sure to click on the **'Update Sign-Ups'** button to register the granted or denied credits into the system.
{% endif %}

{% if study_type == 'lab' and assistant_status == 'y' %}
While your study is running in the lab, the Research Assistants are responsible for updating the participation status of the registered participants. Participants will be paid out at the beginning of the following week for the previous week's participation.

Given that you have requested lab assistants from us, they will mark participants as "participated" or “no-show”. Hence, your only task is to investigate your data, and deny payment if necessary.
{% endif %}

{% if study_type == 'lab' and assistant_status == 'n' %}
While your study is running, you are responsible for updating the participation status of the registered participants. Participants will be paid out after the timeslot deadline ends. To pay out the participants, we will need to know the status of their participation.

Given that you are conducting your lab study yourself, you must mark "participated" or "no-show" yourself. For a smoother process, these two should be carried out as the study is ongoing.

- Participant participated > "Participated"
- Participant no-show, contacted you on time > **"Excused No-Show"**
- Participant no-show, *did not* contact you on time > **'Unexcused No-Show'**


>[!info] <i class="fa-solid fa-info"></i> &nbsp How to navigate to the payment page on SONA 
>
>1. In SONA, locate and click on **'My Studies'**. This will take you to a list of all your posted studies. 
>2. Among your studies, find the specific study for which you want to grant or deny payments and click on it. This action will display the study's details.
>3. Under the study details, click on **'View/Administer Time slots'**. You will see a display showing the current schedule and time slots for the study.
>3. To grant or deny payment for a specific time slot, click on **'Modify'** next to that time slot.
>4. Here, within the **'Sign-Ups' section**, you'll find a table listing the participants scheduled for that time slot.
>5. Grant or deny payment based on the instructions below.
>6. Carefully check that no students are left with the status "No action taken". You can check these in the tab **"Uncredited sign-ups"**
>7. After making your selections for each participant, scroll down to the bottom of the table and make sure to click on the **'Update Sign-Ups'** button to register the granted or denied credits into the system.

After the study has been completed, you can deny payment if necessary.
{% endif %}

## Conditions under which you can deny payment
- The participant **did not give consent**, and, therefore, did not participate in the study.
- The participant **did not finish** the study. You cannot deny payment if the participant skipped questions but finalized the study.
- The participant failed an **attention check**.
- The participant completed the task at an **unusually rapid pace**, identified as being more than 3 standard deviations faster than the average.
- The participant **clearly did not show effort** for the study, even though you have *explicitly specified* the amount of effort you are expecting. For example, when explicitly asked to write a paragraph, they only wrote a couple of words, or for the entire survey, they chose the same point on a Likert scale.

## How to deny payment
To deny payment to a participant, because of any of these conditions, keep their status as "participated", but add a comment "Payment denied: `{...}`" with filling in the `{...}` field with the appropriate reasoning (e.g., "failed attention check"). This comment will be visible to the students. Please do not deviate from the wording "Payment denied" at the beginning of the comment. You HAVE TO add such comments if you would like to deny payment.

>[!info] <i class="fa-solid fa-info"></i> &nbsp Do you have an incentivized study? 
><br>
> For incentivized studies, you can also arrange the incentive payment through the payment page on SONA. 
>
> Example: 
> 
> - You have a performance task in your research and you incentivize participants by paying 15 EUR for the top 10 best performing participants.
> - After your study is concluded, you identify the top 10. 
> - On the payment page on SONA (same page as described above), for each of these 10 participants, you should enter "Incentive: 15" as a comment. 
> - We will make the payment according to these comments, hence, please do not deviate from the format of "Incentive: `{amount}`".
> - You have 2 business working days after the deadline to add the incentivized amount. After the 2 business days, we will begin processing payments and you cannot deny payments to participants thereafter.

We will review the status of participants on SONA after the timeslot deadline.

*NOTE: You have 2 business days after the deadline to review your data and deny payments. After that, we will begin processing payments and you cannot deny payments to participants thereafter.*

We will initiate the payment process with the budget holder and the finance department to ensure that participants are paid on time. The budget holder must respond to the payment request email with everyone in CC to approve it. During the holiday season, it is the responsibility of the researcher/budget holder to ensure that payment emails are answered.
 
This will be done after the deadline of every timeslot you have for your study.