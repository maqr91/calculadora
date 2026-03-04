<!-- ✅ Footer fijo con Privacy/Terms (pegalo antes de </body>) -->
<div id="legal-footer">
  <a href="privacy.html" target="_blank" rel="noopener">Privacy Policy</a>
  <span class="sep">•</span>
  <a href="terms.html" target="_blank" rel="noopener">Terms & Conditions</a>
</div>

<style>
  #legal-footer{
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 9999;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 12px;
    padding: 10px 12px;
    background: rgba(11,31,58,.92); /* navy */
    backdrop-filter: blur(6px);
    border-top: 1px solid rgba(255,255,255,.12);
    font-family: Arial, sans-serif;
    font-size: 13px;
  }
  #legal-footer a{
    color: #ffd1a6; /* tu naranja pastel */
    text-decoration: none;
    font-weight: 700;
  }
  #legal-footer a:hover{
    text-decoration: underline;
  }
  #legal-footer .sep{
    color: rgba(255,255,255,.6);
  }

  /* Para que el footer no tape contenido al final */
  body{ padding-bottom: 60px; }
</style>
