## Hi there 👋

<!--
**Norbo91/Norbo91** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
version: 2
build:
  os: ubuntu-24.04
  tools:
    python: "3.14"
    # You can also specify other tool versions:
    # nodejs: "24"

# Build documentation in the docs/ directory with Sphinx
sphinx:
   configuration: docs/conf.py

# Dependencies required to build your docs
python:
   install:
   - requirements: docs/requirements.txt
