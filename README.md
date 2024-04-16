<!----# Hi, I'm :sparkles:_**Kotyga Mayya**_:sparkles:---->

<p> <img src=https://komarev.com/ghpvc/?username=Kotyga alt=Kotyga /> </p>

<center>I'm middle data analyst </center>

<div style="display: flex; justify-content: center;">
  <img alig src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kotyga&theme=nord_bright" />
</div>

<div style="display: flex; justify-content: center;">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Kotyga&theme=nord_bright" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Kotyga&theme=nord_bright" />
</div>

<div style="display: flex; justify-content: center;">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Kotyga&theme=nord_bright" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Kotyga&theme=nord_bright" />
</div>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ Kotyga }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

<p align="center">
  <img alig src="https://github-profile-trophy.vercel.app/?username=Kotyga&column=8&rank=SSS,SS,S,AAA,AA,A,B,C" />
</p>
