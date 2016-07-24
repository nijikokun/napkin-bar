# The Napkin Bar

Curated links for the best design choices you can make for your software.

**Terminology**

- **DDD** - [Domain Driven Design][ddd-wikipedia]
- **FF** or **FTF** - Function First Design, or File-type First Design is structuring your application by it's function before the files such as a directory named `components` containing all component files.

**File Structure**

Structuring applications is hard, here are a few resources to help. 
Most are Domain Driven Design (DDD). It's powerful and works for small to large scale applications.

- **Ember**
  - [How to use Pods Structure][how-to-use-pods-ember]
    - Takeaways: DDD Structure
  - [Organize File Structure with Ember Pods][organize-structure-ember]
    - Takeaways: DDD Structure
  - [Two techniques to organize Ember][two-organize-ember]
    - Takeaways: DDD Structure, Utilities for common template code.
  - Notes:
    - DDD Design for Ember is called "Pods"
    - Utility functions wrapping modules for templating is powerful, DRY techniques.
    - Tests inside the Pod is a powerful function of DDD, as evident in Python and other languages.
- **React**
  - [Organize For Scale][organize-for-scale-react]
    - Takeaways: DDD Structure, FTF has flaws and why, Organize styles in DDD structured fashion as well.
  - [Folder Structure][folder-structure-react]
    - Takeaways: DD-ish Structure, Tests under domain structure easier to manage. 
  - [Better File Structure][better-file-structure-react]
    - Takeaways: DDD Structure, Tests same folder using `-spec`, tests test whole component.
  - [Organizing Redux][organizing-redux-react]
    - Takeaways: DD-ish Structure, avoid coupling state to component, avoid circular deps.

**Code Structure**

- **Components**
  - [Container Components][container-components-react] - Written for React, can be applied to all frameworks.
    - Takeaways: Separate concerns, presentation (rendering) vs computation (fetching & validation & processing)
  - [Children Components][children-components-react]
    - Takeaways: Pass children to component, separation of parent and child, easier testing.
  - [Component Communication][component-communication-react]
    - Takeaways: There are many ways to do communication between components.
  - [Higher Order Components][higher-order-components-react]
    - Takeaways: Dependency injection pattern for React Components.

**FAQ**

- **Q**: I think I have too many Components, how many is too many?
  - **A**: [You can never have too many.](https://twitter.com/poshaughnessy/status/542768271427375104)

**Further Reading**

- **Articles**
  - [You don't need lodash or underscore][no-underscore-lodash-article]
- **Books**
  - [Domain Driven Design][ddd-amazon]
  - [Implementing Domain Driven Design][ddd-implement-amazon]
  - [Patterns of Enterprise Application Architecture][enterprise-patterns-amazon]
  - [Design Patterns][design-patterns-amazon]
- **Patterns**
  - Domain Driven Design
  - Aspect Oriented Programming

[no-underscore-lodash-article]: https://github.com/cht8687/You-Dont-Need-Lodash-Underscore

[organize-for-scale-react]: http://engineering.kapost.com/2016/01/organizing-large-react-applications/
[folder-structure-react]: https://gist.github.com/ryanflorence/daafb1e3cb8ad740b346
[better-file-structure-react]: http://marmelab.com/blog/2015/12/17/react-directory-structure.html
[organizing-redux-react]: http://jaysoo.ca/2016/02/28/organizing-redux-application/
[container-components-react]: https://css-tricks.com/learning-react-container-components/
[children-components-react]: http://buildwithreact.com/article/component-children
[component-communication-react]: http://andrewhfarmer.com/component-communication/
[higher-order-components-react]: https://medium.com/@dan_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750#.eg35rfocr

[organize-structure-ember]: http://cball.me/organize-your-ember-app-with-pods/
[how-to-use-pods-ember]: http://www.programwitherik.com/ember-pods/
[two-organize-ember]: https://spin.atomicobject.com/2015/09/17/ember-js-clean/

[ddd-wikipedia]: https://en.wikipedia.org/wiki/Domain-driven_design

[ddd-amazon]: https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215
[ddd-implement-amazon]: https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577/
[enterprise-patterns-amazon]: https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/
[design-patterns-amazon]: https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612/
