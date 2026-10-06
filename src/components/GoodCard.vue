<template>
  <section class="card">
    <h2>✅ Mit Tokens</h2>
    <span class="badge">Neu</span>
    <a href="#" class="link">Mehr erfahren</a>
    <button class="btn">Speichern</button>
  </section>
</template>

<!-- Dieselbe Farbe überall über --color-primary: eine Änderung in tokens.css reicht -->
<style scoped>
.card {
  background: var(--color-surface);
  padding: var(--space-l);
  border-radius: var(--radius);
  width: 20rem;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: var(--space-m);
}
.badge {
  color: var(--color-primary);
  border: 1px solid var(--color-primary);
  padding: var(--space-s);
  border-radius: var(--radius);
}
.link {
  /* Fallback: greift, wenn --color-primary nicht definiert ist (z. B. tokens.css fehlt) */
  color: var(--color-primary, #2563eb);
}

.btn {
  background: var(--button-bg);
  color: var(--button-text);
  padding: var(--button-padding);
  border: 0;
  border-radius: var(--button-radius);
}
</style>
