<template>
  <section class="card">
    <h2>❌ Anti-Pattern</h2>
    <span class="badge">Neu</span>
    <a href="#" class="link">Mehr erfahren</a>
    <button class="btn">Speichern</button>
  </section>
</template>

<!-- Dieselbe Farbe und dieselben Abstände überall einzeln hart codiert:
     eine Änderung bedeutet, jede Stelle (und jede Komponente) anzufassen -->
<style scoped>
.card {
  background: #f3f4f6;
  padding: 24px;
  border-radius: 8px;
  width: 20rem;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
}
.badge {
  color: #2563eb;
  border: 1px solid #2563eb;
  padding: 8px;
  border-radius: 8px;
}
.link {
  color: #2563eb;
}
.btn {
  background: #2563eb;
  color: white;
  padding: 8px 16px;
  border: 0;
  border-radius: 8px;
}
</style>
