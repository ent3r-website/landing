<template>
  <div>
    <p>
      Links to stuff I've made, stuff I find interesting, or just generally
      other things you should have a look at.
    </p>

    <table>
      <tbody>
        <tr>
          <td>
            <a
              href="https://www.hackthebox.eu/home/users/profile/266080"
              target="_blank"
              rel="noopener noreferrer"
              >HackTheBox</a
            >
          </td>
          <td>My HackTheBox profile</td>
        </tr>
        <tr>
          <td>
            <a
              href="https://github.com/CTFNote"
              target="_blank"
              rel="noopener noreferrer"
              >CTFNote</a
            >
          </td>
          <td>
            CTFNote is a notepad and tool for CTF teams to better manage and
            organize CTFs and CTF challenges.
          </td>
        </tr>
        <tr>
          <td>
            <a
              :href="`https://github.com/${$globalVars.github_username}/dotfiles`"
              target="_blank"
              rel="noopener noreferrer"
              >dotfiles</a
            >
          </td>
          <td>The repo with all my dotfiles and stuff</td>
        </tr>
        <tr>
          <td>
            <a
              href="https://corax.team"
              target="_blank"
              rel="noopener noreferrer"
              >Team Corax</a
            >
          </td>
          <td>The CTF team I'm a part of.</td>
        </tr>
        <tr>
          <td>
            <a
              href="https://nerd.s1lv3r.codes"
              target="_blank"
              rel="noopener noreferrer"
              >nerd.s1lv3r.codes</a
            >
          </td>
          <td>Nerd</td>
        </tr>
        <tr>
          <td>
            <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">Very cool</a>
          </td>
          <td>Such a cool website</td>
        </tr>
        <tr>
          <td>
            <a
              :href="`https://github.com/${$globalVars.repo}`"
              target="_blank"
              rel="noopener noreferrer"
              >{{ $globalVars.repo }}</a
            >
          </td>
          <td>The GitHub repository for this website</td>
        </tr>
        <tr>
          <td>
            <a href="https://github.com/theS1LV3R">theS1LV3R</a>
          </td>
          <td>My GitHub page</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  head: {
    title: 'Links',
  },
})
</script>
