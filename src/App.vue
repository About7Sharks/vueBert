<template>
  <h1 style="margin-bottom:10px">AI Genie</h1>
  <div style="max-width:400px"><p>The model can be used to build a system that can answer users’ questions in natural language. It was created using a pre-trained BERT model fine-tuned on SQuAD 2.0 dataset.</p>
  <p>The model takes a passage and a question as input, then returns a segment of the passage that most likely answers the question. It requires semi-complex pre-processing including tokenization and post-processing steps that are described in the BERT paper and implemented in the sample app. This model is also available in TFLite.</p>
  </div>
  <br>
  <Tensor />
</template>

<script setup>
import Tensor from './components/Tesnor.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */

  /* background: url('https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.imgur.com%2FUwuqHf6.jpg&f=1&nofb=1'); */
  background-size: cover;
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  width: 100vw;
  height: 100vh;
}
body{
  margin: 0px;
  padding: 0px;
}
</style>
