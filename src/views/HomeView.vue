<script setup></script>

<template>
  <main>
    <h1>Weather-Aware IoT clothes drying system</h1>
    <iframe
      width="1200"
      height="900"
      src="https://cloudwatch.amazonaws.com/dashboard.html?dashboard=smart-rack&context=eyJSIjoidXMtZWFzdC0xIiwiRCI6ImN3LWRiLTYwMDYyNzM0MDI0NCIsIlUiOiJ1cy1lYXN0LTFfaDhVZjRwZFlNIiwiQyI6IjR2bDY4YmFnaTZvbWFhcDIyNjY0YjlodHJpIiwiSSI6InVzLWVhc3QtMTo3ZjEzMzk2My0yMWVlLTQ2NTctYTI4MC1jOWQ2MzM2YzU3M2YiLCJPIjoiYXJuOmF3czppYW06OjYwMDYyNzM0MDI0NDpyb2xlL3NlcnZpY2Utcm9sZS9DV0RCU2hhcmluZy1QdWJsaWNSZWFkT25seUFjY2Vzcy03MDNJWVFCNSIsIk0iOiJQdWJsaWMifQ%3D%3D&utm_source=zalo&utm_medium=zalo&utm_campaign=zalo&start=PT1H&end=null"
      title="IoT Dashboard"
      allowfullscreen
    ></iframe>
  </main>
</template>

<style>
h1 {
  text-align: center;
  padding: 10px;
}
iframe {
  display: block;
  margin: 10px auto;
  border: none;
}

@media (max-width: 1200px) {
  iframe {
    width: 100%;
    height: 600px;
  }
}

@media (max-width: 768px) {
  iframe {
    width: 100%;
    height: 400px;
  }
}

@media (max-width: 480px) {
  iframe {
    width: 100%;
    height: 250px;
  }
}
</style>
