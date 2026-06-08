# Detailed description

For this section, you can **copy and paste the template below** and fill in the empty fields `{...}` with the relevant information for your study.

Please include the required information only:
- Short description
- Payments and processing time
- Duration of study
- Language of study
- Location of study
- Sign-ups & Unexcused No-shows
- Researcher information: name, department, faculty, and email address

Without all of this information, the study will not be approved.

If you would like to add more information about your study, you may do so, but please **do not include any information about your hypotheses or variables**.

{% if study_type == 'online' %}
>[!info] <i class="fa-solid fa-info"></i> &nbsp; Text to copy paste (for an online study)
><br>
>**Short description:** `{...}`
>
>**Payments and processing time:** You will receive `{...}` EUR for completing this study. Payments will be processed `{...}`.
>
>**Duration of study:** This study will take approximately `{...}` minutes.
>
>**Language of study:** The study language is `{...}`.
>
>**Location of study:** This study will take place `{...}`.
>
>**Sign-ups & Unexcused No-shows:** `{...}`
>
>**Researcher information:** This study is organized by `{name}`, Department of `{department}`, `{faculty}`, Vrije Universiteit Amsterdam, `{email}` `{(if applicable) in collaboration with researchers from ...}`.
{% endif %}

{% if study_type == 'lab' %}
{% if faculty == 'SBE' %}
>[!info] <i class="fa-solid fa-info"></i> &nbsp; Text to copy paste (for a physical lab study)
><br>
>**Short description:** `{...}`
>
>**Payments and processing time:** `{...}`
>
>**Duration of study:** This study will take approximately `{...}` minutes.
>
>**Language of study:** The study language is `{...}`.
>
>**Location of study:** This research takes place in the Applied Behavioural Science Lab, located on the second basement level (-2) of the [Transitorium Building](https://vu.nl/en/about-vu/more-about/transitorium).
>
>**Sign-ups & Unexcused No-shows:** You must register for a spot in the available time slots. Please be present in the waiting area at least 5 minutes in advance. The session starts right on time, and access to the lab after the start time will be denied.
>
>**Researcher information:** This study is organized by `{name}`, Department of `{department}`, `{faculty}`, Vrije Universiteit Amsterdam, `{email}` `{(if applicable) in collaboration with researchers from ...}`.
>
>You can see your Sona ID in your Sona account or in the confirmation email. It is a 4 or 5-digit number and is **not** your student ID.
{% endif %}

{% if faculty == 'FGB' %}
As a researcher from FGB, you need to arrange the labs yourself. If you will be using the Brain & Behaviour Labs facilities, please consult the [BBLabs Documentation](https://brainbehavior.labs.vu.nl/docs#/){:target="_blank" rel="noopener noreferrer"}.

Importantly, if your experiment is a **walk-in study**, start the description with the word “walk-in” and describe when and where students can show up to participate in your study.

>[!info] <i class="fa-solid fa-info"></i> &nbsp; Text to copy paste (for a physical lab study)
><br>
>**Short description:** `{...}`
>
>**Payments and processing time:** `{...}`
>
>**Duration of study:** This study will take approximately `{...}` minutes.
>
>**Language of study:** The study language is `{...}`.
>
>**Location of study:** `{...}`
>
>**Sign-ups & Unexcused No-shows:** `{...}`
>
>**Researcher information:** This study is organized by `{name}`, Department of `{department}`, `{faculty}`, Vrije Universiteit Amsterdam, `{email}` `{(if applicable) in collaboration with researchers from ...}`.
>
>**Walk-in:** `{is / is not}` possible. If walk-in is possible, please specify when and where students can show up.
{% endif %}
{% endif %}