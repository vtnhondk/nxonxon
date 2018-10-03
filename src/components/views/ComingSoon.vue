<template>
  <div>
    <div class="header">
      <h1 class="author">{{ author }} - {{ year }}</h1>
    </div>
    <div class="center">
      <span class="title">This site is</span>
      <span class="content">Coming Soon</span>
      <div class="social">
        <ul>
          <li>
            <a href="https://github.com/vtnhondk" target="blank">
              <i class="fab fa-github" />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script src="https://unpkg.com/marked@0.3.6"/>
<script src="https://unpkg.com/lodash@4.16.0"/>
<script src="../scripts/ComingSoon.js"/>
<style src="../styles/ComingSoon.css"/>