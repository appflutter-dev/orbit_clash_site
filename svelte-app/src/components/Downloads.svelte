<script>
  let googlePlayRating = "?";
  let appStoreRating = null;
  let amazonStoreRating = 5;
</script>

<section>
  <div class="store-links">
    <a
      class="store-link"
      href="https://play.google.com/store/apps/details?id=com.fsa.orbit_clash"
      target="_blank"
    >
      <img
        src="google-play-badge.png"
        alt="Google Play Store"
        class:grayed-out={googlePlayRating === null}
      />
      <p>
        {googlePlayRating !== null
          ? `Rating: ${googlePlayRating}/5`
          : "Not available"}
      </p>
    </a>
    <a
      class="store-link"
      href="https://apps.apple.com/app/savings-planner/id1234567890"
      target="_blank"
    >
      <img
        src="app-store-badge.svg"
        alt="Apple App Store"
        class:grayed-out={appStoreRating === null}
      />
      <p>
        {appStoreRating !== null
          ? `Rating: ${appStoreRating}/5`
          : "Not available"}
      </p>
    </a>
    <a
      class="store-link"
      href="https://www.amazon.com/gp/mas/dl/android?p=com.fsa.orbit_clash"
      target="_blank"
    >
      <img
        src="amazon-store-badge.jpg"
        alt="Amazon Store"
        class:grayed-out={amazonStoreRating === null}
      />
      <p>
        {amazonStoreRating !== null
          ? `Rating: ${amazonStoreRating}/5`
          : "Not available"}
      </p>
    </a>
  </div>
</section>

<style>
  .store-links {
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
  }

  .store-link {
    text-align: center;
    margin: 1rem;
  }

  .store-link img {
    width: 150px;
    margin: 0.5rem;
    transition: opacity 0.3s;
  }

  .store-link img.grayed-out {
    opacity: 0.5;
  }
</style>
