# Your responsibility during data collection

{% if study_type == 'online' or assistant_status == 'y'%}
As soon as the study details have been approved by us, your study will be launched and advertised to the students. Please keep an eye out on participant registration.

{% if study_type == 'online'%}
For **your online study**, students can enroll and participate directly.
{% endif %}
{% if assistant_status == 'y' %}
Given that you are requesting lab assistants from us, we will arrange your lab study by opening time slots on SONA, and arranging the study in the Transitorium building or elsewhere. You as a researcher do not have a responsibility during this process.
{% endif %}

Although, we do recommend that you already check out now what needs to be done after data collection by following the next steps, so that you know what to expect. 
{% endif %}

{% if faculty == 'FGB' and study_type == 'lab' %}
## Arranging Lab Access

As an FGB researcher, you must arrange access to the Brain & Behaviour Labs facilities before your study begins. Consult the <u>**[BBLabs Documentation](https://bblabs.fgb.vu.nl/books/brain-behaviour-lab)**</u> for access procedures.

## Scheduling Options

**Time slot-based studies:**
If participants sign up for specific sessions, you must create time slots in SONA before launching your study. Once launched, students will enroll in the available slots created by you or your research assistants.

**Walk-in studies:**
If your study allows walk-in participation, clearly state this in your study description so participants know they can attend without booking a specific time.
{% endif %}

{% if faculty == 'SBE' and study_type == 'lab' and assistant_status == 'n' %}
Now that your study has been created, check the lab availability calendar again and email us to confirm your room booking, as covered in Step 1. Once your booking is confirmed, follow these steps:

## Scheduling Options

**Time slot-based studies:**
If participants sign up for specific sessions, you must create time slots in SONA before launching your study. Once launched, students will enroll in the available slots created by you.

**Walk-in studies:**
If your study allows walk-in participation, clearly state this in your study description so participants know they can attend without booking a specific time.

## Lab access
After your research dates are confirmed, you need to arrange access to the Transitorium building. See the following pages for detailed instructions on arranging time slots and building access.
{% endif %}