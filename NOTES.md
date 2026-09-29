Creating a branch allows you to create a copy inside of a project, so you can separate your features from main projects while their development.
Also it allows you to create different environments for your projects (stage, dev, etc). Such way of creating separated environments is called "monorepo" - one repo which contains many environments of one project with the help of branches.

git merge vs git rebase:
git merge saves tree-hierarchy of commits and creates one merge commit from your separate branch and the main one, while git rebase makes commits' history linear by adding commits from your swparate branch on top of thr main one. It can cause damage of project's history if you're working in team.