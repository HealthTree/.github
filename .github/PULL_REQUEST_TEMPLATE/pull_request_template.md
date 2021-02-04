## Description

- Tell us what you did
- Include extra steps
- Try to leave the functional testing creativity to the reviewer

## Proposed changes

- X
- Y
- Z

## Links

Fixes # .
Close # .

- Link(s) to related 3rd party documentation, solved issue(s), commit(s) & PR(s)

## Please review

Team! pls review 🧐 , make suggestions 🗣, point errors 🐞, comment 💬 and approve ✅ when you feel is ready!

– – – – – – – ✂️ cut here ✂️ – – – – – – –

## **General Guidelines**

[healthtree/guidelines](https://github.com/healthtree/guidelines)

- What's a [good Pull Request](https://github.com/HealthTree/guidelines/blob/master/engineering/git/PRs.md)
- Clean commits history (squashed, atomic, [semantic](https://github.com/HealthTree/guidelines/blob/master/engineering/git/commits.md#semantic-commits) & [meaningful](https://github.com/HealthTree/guidelines/blob/master/engineering/git/commits.md#message-body))
- Cleanup
    - Consider refactoring from scratch for big features
    - Avoid making Redux' mud ball bigger
    - Use `/services` for data fetching
    - Remove unnecesary/legacy code & comments
    - Fix complex logic as much as possible
    - Remember Ken Thompson productivity: https://twitter.com/codewisdom/status/1004045276292661249
- Styling HTML & CSS
    - Make use of [CSS Modules](https://github.com/healthtree/guidelines#css-modules) to avoid polluting the global namespace
    - Use CSS Flexbox to make content responsive
- [React best practices and design patterns](https://github.com/healthtree/guidelines#react)
- [State Management](https://github.com/healthtree/guidelines#state-management)
    - If no complex state sharing is needed, consider using React `this.state` only
    - If more complex state management is needed, consider using:
        - [Context API](https://reactjs.org/docs/context.html) for sharing simple state between a Component Tree ([using new Hooks API](https://kentcdodds.com/blog/application-state-management-with-react) is also OK!)
        - [MobX](https://mobx.js.org/intro/overview.html) for more complex stores with lots of values
    - Use [Formik](https://jaredpalmer.com/formik/) when making _heavy use of Forms_ to avoid complex boilerplate
- [Test-driven Development (Integration, Unit, etc)](https://github.com/HealthTree/guidelines/blob/master/README.md#testing-1)
    - Test sensitive use-cases
    - Increase test code coverage
    - You can [exclude or focus on tests](https://facebook.github.io/create-react-app/docs/running-tests#focusing-and-excluding-tests) _while developing only_
- Update Wiki Documentation if needed
