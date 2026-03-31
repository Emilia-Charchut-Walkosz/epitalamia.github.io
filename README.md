# epitalamia.github.io
  /* Subtelna linia u góry w kolorze karmyzynowym */
  .site-header::before {
    content: '';
    display: block;
    height: 4px;
    background: var(--crimson);
  }

  .header-inner {
    max-width: 1200px;
    margin: 0 auto;
    padding: 36px 48px 28px;
    text-align: center;
    position: relative;
  }

.header-rule {
    display: flex;
    align-items: center;
    gap: 14px;
    margin-bottom: 14px;

.header-rule::before, .header-rule::after {
    content: '';
    flex: 1;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--sepia-pale), transparent);

