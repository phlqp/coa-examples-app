<template>
  <div class="container">
    <h1>COA Examples</h1>
    <div class="links-section">
      <h2>SharePoint Documents</h2>
      <ul class="links-list">
        <li>
          <a 
            href="https://koicbd.sharepoint.com/:b:/s/KoiMarketing/ET4DDrGEERBLnB-blDZjQPUBlY2205KhyoqPgzgifMHCYA?e=d0lO6Y"
            target="_blank"
            rel="noopener noreferrer"
            class="link-item"
          >
            Document 1 - KoiMarketing SharePoint
          </a>
        </li>
        <li>
          <a 
            href="https://koicbd.sharepoint.com/:b:/s/KoiMarketing/EUlbngJ0g6pAt2oMxi5DvmABEzip-SjVxGKiloCotTPRCQ?e=SxnYZt"
            target="_blank"
            rel="noopener noreferrer"
            class="link-item"
          >
            Document 2 - KoiMarketing SharePoint
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script setup lang="ts">
// Set page metadata
useHead({
  title: 'COA Examples',
  meta: [
    { name: 'description', content: 'Access COA example documents from SharePoint' }
  ]
})
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
  font-family: Arial, sans-serif;
}

h1 {
  color: #333;
  margin-bottom: 2rem;
  text-align: center;
}

h2 {
  color: #555;
  margin-bottom: 1rem;
}

.links-section {
  background: #f9f9f9;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.links-list {
  list-style: none;
  padding: 0;
}

.links-list li {
  margin-bottom: 1rem;
}

.link-item {
  display: inline-block;
  padding: 1rem 1.5rem;
  background: #007acc;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
  font-weight: 500;
}

.link-item:hover {
  background: #005999;
}

.link-item:focus {
  outline: 2px solid #004d7a;
  outline-offset: 2px;
}
</style>