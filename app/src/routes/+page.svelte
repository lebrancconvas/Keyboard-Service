<script lang="ts">


</script>

<svelte:head>
  <title>Keyboard Service</title>
</svelte:head>

<main>
  <header>
    <h1>Keyboard Service</h1>
  </header>
  <section id="region-selection-section">
    <label for="region">Region</label>
    <select name="region" id="region">
      <option value="chinese-sim">Chinese (Simplified)</option>
      <option value="chinese-tra">Chinese (Traditional)</option>
      <option value="japanese">Japanese</option>
      <option value="korean">Korean</option>
    </select>
    <button>Select</button>
  </section>
  <footer>
    <p>Created by <a href="https://github.com/lebrancconvas" target="_blank">Poom Yimyuean (@lebrancconvas)</a> | <a href="https://github.com/lebrancconvas/Keyboard-Service" target="_blank">View Github</a></p>
  </footer>
</main>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Kanit', sans-serif;
  }

  header {
    text-align: center;
  }

  #region-selection-section {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
  }

  #region-selection-section button {
    
  }

  footer {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 50px;
    text-align: center;
    background-color: rgb(100, 170, 216);
  }

  footer p {
    font-size: 20px;
  }
</style>
