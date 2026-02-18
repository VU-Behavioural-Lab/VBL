<section class="faq">
  <h1>Frequently Asked Questions</h1>

  <!-- Tab Navigation -->
  <div class="faq-tabs">
    <button class="faq-tab active" onclick="switchTab('researchers')">For Researchers</button>
    <button class="faq-tab" onclick="switchTab('students')">For Students</button>
  </div>

  <!-- Researchers FAQs -->
  <div id="researchers-faq" class="faq-section active">
    <details class="faq-item">
      <summary>
        <span class="q">How will payments be allocated to participants?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        <p>
        Participant payment information is securely stored within the system and is only accessible to the lab administrator. 
        Researchers must update participant status in SONA within 2 business days after each timeslot deadline. 
        The VBL team then reviews these statuses, contacts budget holders for approval, and processes payments. For detailed instructions on updating participant status, denying payment, and handling special cases, see: <a href="/granting-or-denying-payment"><strong><u>Granting or Denying Payment</u></strong></a>.
        </p>
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">Acknowledgements in paper</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        Please add the following statement in the Acknowledgments section of your manuscript: <strong>We thank the VU Behavioral Lab (Vrije Universiteit Amsterdam) for participant recruitment, lab usage, and data collection support</strong>.
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">How long in advance should I request a study?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        Due to planning and registering, we require you to request physical lab studies at least 3 weeks / online studies at least 2 weeks before the session takes place, but preferably even earlier. 
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">Will my study be deactivated if there are no new time slots?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        Yes. If no new time slots are added within 3 months, your study will be deactivated. This ensures that the system only displays active and available studies for participants.
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">I would like to invite an external researcher to the study.</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        Unfortunately, no external researchers are allowed to access the system. You can manage as a collaborator on their behalf.
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">I would like to invite an external participant to the study.</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        Unfortunately, at the moment, external participants cannot sign up or receive payments through the system.
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">Can I use prescreeners to select participants for my study?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        Prescreeners are standard questionnaires (e.g., demographic or personality surveys) that participants fill out once a year. These are stored outside of SONA and used to help researchers access important participant information without having to collect it repeatedly for every study. <strong> Due to VU's data privacy and storage policies, prescreening data is not stored in SONA and cannot be used to automatically filter or preselect participants for your study.</strong> While you can specify eligibility criteria (e.g., gender, age) in your SONA study description, students may overlook these and still register. As a researcher, you retain the right to reject ineligible participants or exclude their data. Please note that applying eligibility restrictions may significantly reduce your participant pool.
      </div>
    </details>
  </div>

  <!-- Students FAQs -->
  <div id="students-faq" class="faq-section">
    <details class="faq-item">
      <summary>
        <span class="q">How long does the participant payment usually take?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        We typically process payments within <strong>2 weeks</strong>, though this may take longer during holidays or summer break. Payment timelines can vary by study, so please check the study description for specific details.
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">What happens if I provided the wrong payment information?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        If the payment information you provided is incorrect and we are unable to process your payout, we will contact you to request updated details. If we do not receive a response within 14 days, the payout may be forfeited. Therefore, please ensure your payment information is accurate to avoid delays or loss of payment.
      </div>
    </details>

    <details class="faq-item">
      <summary>
        <span class="q">How can I update my payment information?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        If your payment information changed, please reach out to us via <a href="mailto:vbl@vu.nl">vbl@vu.nl</a>. We will delete your information in the system and you can then enter your correct or updated information.
      </div>
    </details>
  </div>

  <!-- General FAQ (visible in both) -->
  <div class="faq-general">
    <details class="faq-item">
      <summary>
        <span class="q">Who is the VU Student Pool and when are they available?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        The VU Student Pool consists of students from various academic backgrounds who participate in behavioural and cognitive research studies. They are available throughout the entire calendar year. 
      </div>
    </details>
    <details class="faq-item">
      <summary>
        <span class="q">My question is not mentioned here?</span>
        <span class="chev" aria-hidden="true"></span>
      </summary>
      <div class="a">
        If your payment information has changed, please contact us at <a href="mailto:vbl@vu.nl">vbl@vu.nl</a>. We will remove your existing details from our system so that you can submit your updated payment information.
      </div>
    </details>
  </div>
</section>

<script>
function switchTab(audience) {
  // Remove active class from all tabs and sections
  document.querySelectorAll('.faq-tab').forEach(tab => tab.classList.remove('active'));
  document.querySelectorAll('.faq-section').forEach(section => section.classList.remove('active'));
  
  // Add active class to clicked tab and corresponding section
  event.target.classList.add('active');
  document.getElementById(audience + '-faq').classList.add('active');
}
</script>

<style>
  /* Container */
  .faq{
    --bg: #ffffff;
    --card: #f9fafb;
    --muted: #4b5563;
    --text: #000000;
    --accent: #005c8e; 
    --border: #d1d5db;

    max-width: 760px;
    margin: 3rem auto;
    padding: 0 1rem;
    color: var(--text);
    font: 16px/1.5 ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
  }

  .faq h1{
    font-size: clamp(1.6rem, 3vw, 2.2rem);
    font-weight: 800;
    margin: 0 0 1.25rem;
    letter-spacing: -0.02em;
    color: var(--text);
  }

  /* Tabs */
  .faq-tabs{
    display: flex;
    gap: 0.5rem;
    margin-bottom: 1.5rem;
    border-bottom: 2px solid var(--border);
  }

  .faq-tab{
    padding: 0.75rem 1.5rem;
    background: transparent;
    border: none;
    border-bottom: 3px solid transparent;
    font-weight: 600;
    font-size: 1rem;
    cursor: pointer;
    color: var(--muted);
    transition: all 0.2s ease;
    margin-bottom: -2px;
  }

  .faq-tab:hover{
    color: var(--accent);
  }

  .faq-tab.active{
    color: var(--accent);
    border-bottom-color: var(--accent);
  }

  /* Sections */
  .faq-section{
    display: none;
  }

  .faq-section.active{
    display: block;
  }

  .faq-general{
    margin-top: 2rem;
    padding-top: 2rem;
    border-top: 2px solid var(--border);
  }

  /* Card-like details */
  .faq-item{
    border: 1px solid var(--border);
    border-radius: 16px;
    background: var(--card);
    margin: 0 0 0.75rem;
    overflow: clip;
  }

  /* Remove default marker */
  .faq-item summary { list-style: none; }
  .faq-item summary::-webkit-details-marker { display: none; }

  /* Summary (question) */
  .faq-item summary{
    display: grid;
    grid-template-columns: 1fr auto;
    align-items: center;
    gap: .75rem;
    padding: 1rem 1.1rem 1rem 1rem;
    cursor: pointer;
    position: relative;
  }

  .faq-item summary .q{
    font-weight: 700;
    letter-spacing: -0.01em;
    display: inline-flex;
    align-items: center;
    gap: .5rem;
  }

  /* Chevron */
  .faq-item .chev{
    width: 1.1rem; height: 1.1rem;
    border-right: 2px solid var(--muted);
    border-bottom: 2px solid var(--muted);
    transform: rotate(-45deg);
    transition: transform .25s ease, border-color .25s ease;
    opacity: .9;
  }
  .faq-item[open] .chev{
    transform: rotate(45deg);
    border-color: var(--accent);
  }

  /* Answer */
  .faq-item .a{
    padding: 0 1rem 1rem;
    color: var(--muted);
    border-top: 1px solid var(--border);
    background: #fff;
    animation: fadeDown .25s ease;
  }

  /* Hover / focus styles for better affordance */
  .faq-item summary:hover .q{ text-shadow: 0 0 0.5px currentColor; }
  .faq-item summary:focus-visible{
    outline: 3px solid color-mix(in oklab, var(--accent) 50%, transparent);
    outline-offset: 2px;
    border-radius: 14px;
  }

  /* Subtle open/close animation */
  @keyframes fadeDown{
    from{ opacity: 0; translate: 0 -4px; }
    to{ opacity: 1; translate: 0 0; }
  }

  /* Respect reduced motion */
  @media (prefers-reduced-motion: reduce){
    .faq-item .chev{ transition: none; }
    .faq-item .a{ animation: none; }
  }
</style>
