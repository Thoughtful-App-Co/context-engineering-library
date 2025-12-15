A build-book is a modern version of ai powered, ai readable software requirements and building when using prompts ontop of GenAI tools.
Build books should reference a Configuration As a Tech Spec (Cats) and give a verbose checklist of items for the agent to do. Agents like to go 
down the list. At each era (phase,milestone) you will be able to commit and push that part of the build. 
A build book is like a PRD, user stories, combined into one giant build list.

How I imagine build books happening:
filesystem looks like:
{monorepo}/docs/context/build/buildbooks

buildbooks/
  /books - feature level buildouts
    /feature.buildbook.yaml
    /feature2.buildbook.yaml
context/
  cats/
  /feature.cats.yaml
  /templates

uses: (you can build your own, I am not providing it but OpenCode/Cursor uses these a lot)
- plan, build, review
