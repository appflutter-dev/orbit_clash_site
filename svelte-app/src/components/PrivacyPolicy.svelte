<script>
  let contactEmail = "appflutter.development@gmail.com";
</script>

<div class="privacy-policy">
  <h1>Privacy Policy</h1>

  <section>
    <h2>Introduction</h2>
    <p>
      Welcome to the Orbit Clash application (the "App"). This Privacy Policy is
      designed to inform you about how we collect, use, and protect your
      information when you use our App.
    </p>
  </section>

  <section>
    <h2>Information We Collect</h2>
    <p>
      The App itself does not collect any personal data. However, we use AdMob
      by Google for personalized advertisements, which may collect and use your
      data. Please refer to AdMob's privacy policy for more information on the
      data they collect and how it is used.
    </p>
  </section>

  <section>
    <h2>How AdMob Uses Your Data</h2>
    <p>
      AdMob may collect and use data to show personalized ads. This includes,
      but is not limited to:
    </p>
    <ul>
      <li>Device information (e.g., model, OS, unique identifiers)</li>
      <li>IP address</li>
      <li>Usage data and metrics</li>
    </ul>
    <p>
      For detailed information on AdMob’s data collection and processing
      practices, please review the <a
        href="https://policies.google.com/technologies/ads"
        target="_blank">AdMob Privacy Policy</a
      >.
    </p>
  </section>

  <section>
    <h2>GDPR Compliance</h2>
    <p>
      If you are located in the European Economic Area (EEA), you have certain
      rights under the General Data Protection Regulation (GDPR). These rights
      include:
    </p>
    <ul>
      <li>The right to access the data AdMob has about you</li>
      <li>The right to rectify any incorrect data</li>
      <li>The right to erase your data</li>
      <li>The right to restrict or object to the processing of your data</li>
      <li>The right to data portability</li>
    </ul>
    <p>
      You can exercise these rights by contacting Google directly. For more
      information on your rights under GDPR, please refer to the <a
        href="https://gdpr-info.eu/"
        target="_blank">GDPR Information Portal</a
      >.
    </p>
  </section>

  <section>
    <h2>Consent to Personalized Ads</h2>
    <p>
      When you use our App, you may be asked to provide consent for personalized
      ads. You can manage your ad preferences or withdraw your consent at any
      time through the settings on your device or by following the instructions
      provided by AdMob.
    </p>
  </section>

  <section>
    <h2>Data Security</h2>
    <p>
      We are committed to ensuring that your information is secure. Although we
      do not collect personal data directly, we ensure that our third-party
      partners, such as AdMob, use reasonable measures to protect your data.
    </p>
  </section>

  <section>
    <h2>Changes to This Privacy Policy</h2>
    <p>
      We may update this Privacy Policy from time to time. Any changes will be
      posted within the App and will take effect immediately upon posting.
    </p>
  </section>

  <section>
    <h2>Contact Us</h2>
    <p>
      If you have any questions or concerns about this Privacy Policy, please
      contact us at:
    </p>
    <p>Email: <a href={`mailto:${contactEmail}`}>{contactEmail}</a></p>
  </section>
</div>

<style>
  .privacy-policy {
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem;
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  .privacy-policy h1,
  .privacy-policy h2 {
    color: #333;
  }
  .privacy-policy p {
    line-height: 1.6;
  }
  .privacy-policy ul {
    list-style-type: disc;
    padding-left: 1.5rem;
  }
  .privacy-policy a {
    color: #4caf50;
    text-decoration: none;
  }
  .privacy-policy a:hover {
    text-decoration: underline;
  }
</style>
