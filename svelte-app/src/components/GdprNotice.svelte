<script>
  let admobPrivacyPolicyUrl = "https://policies.google.com/privacy";
  let gdprInfoPortalUrl = "https://gdpr-info.eu/";
</script>

<div class="gdpr-notice">
  <h1>GDPR Notice</h1>

  <section>
    <h2>Data Controller</h2>
    <p>
      Orbit Clash does not collect or process personal data directly. The data
      controller for the personalized ads shown in the App is AdMob by Google.
      Please refer to AdMob’s privacy policy for information on their data
      processing practices.
    </p>
    <p>
      <a href={admobPrivacyPolicyUrl} target="_blank">AdMob Privacy Policy</a>
    </p>
  </section>

  <section>
    <h2>Legal Basis for Processing</h2>
    <p>
      The legal basis for processing your data for personalized ads is your
      consent. You can withdraw your consent at any time by adjusting your ad
      settings or contacting AdMob directly.
    </p>
  </section>

  <section>
    <h2>Data Subject Rights</h2>
    <p>Under GDPR, you have the following rights regarding your data:</p>
    <ul>
      <li>Right to access</li>
      <li>Right to rectification</li>
      <li>Right to erasure</li>
      <li>Right to restrict processing</li>
      <li>Right to data portability</li>
      <li>Right to object</li>
    </ul>
    <p>
      To exercise these rights, please contact AdMob as detailed in their
      privacy policy.
    </p>
  </section>

  <section>
    <h2>Complaints</h2>
    <p>
      If you believe your data protection rights have been violated, you have
      the right to lodge a complaint with a supervisory authority in your
      country of residence.
    </p>
    <p>
      <a href={gdprInfoPortalUrl} target="_blank">GDPR Information Portal</a>
    </p>
  </section>
</div>

<style>
  .gdpr-notice {
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem;
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  .gdpr-notice h1,
  .gdpr-notice h2 {
    color: #333;
  }
  .gdpr-notice p {
    line-height: 1.6;
  }
  .gdpr-notice ul {
    list-style-type: disc;
    padding-left: 1.5rem;
  }
  .gdpr-notice a {
    color: #4caf50;
    text-decoration: none;
  }
  .gdpr-notice a:hover {
    text-decoration: underline;
  }
</style>
