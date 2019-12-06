# Fomantic RFCs

> NOTE: This repository only applies to the v3 framework (currently
in development) and not v2.

Many changes, including bug fixes and documentation improvements can be
implemented and reviewed via the normal GitHub pull request workflow.

Some changes though are "substantial", and we ask that these be put
through a bit of a design process and produce a consensus among the
Fomantic core team.

The "RFC" (request for comments) process is intended to provide a
consistent and controlled path for new features to enter the project.

[Active RFC List](https://github.com/fomantic/rfcs/pulls)

Fomantic is still **actively developing** this process, and it will still
change as more features are implemented and the community settles on
specific approaches to feature development.

## When to follow this process

You should consider using this process if you intend to make "substantial"
changes to Fomantic or its documentation. Some examples that would benefit
from an RFC are:
  - A new component
  - A new feature to a components API like a new setting or method
  - The removal of features that already shipped as part of the release
    channel.

The RFC process is a great opportunity to get more eyeballs on your
proposal before it becomes a part of a released version of Fomantic.
Quite often, even proposals that seem "obvious" can be significantly
improved once a wider group of interested people have a chance to weigh in.

The RFC process can also be helpful to encourage discussions about a
proposed feature as it is being designed, and incorporate important
constraints into the design while it's easier to change, before the design
has been fully implemented.

Some changes do not require an RFC:
  - Rephrasing, reorganizing or refactoring
  - Addition or removal of warnings/debug messages
  - Additions that strictly improve objective, numerical quality criteria
    (performance, better browser support)

## How to submit an RFC

To submit a new RFC, follow these steps:

1. Fork the RFC [repository](https://github.com/fomantic/rfcs).
2. Create a directory inside the `proposed` directory. The directory name.
   should begin with the year followed by a meaningful description, such as
   `text/2019-add-utility-helpers`.
3. Copy the [`template.md`](/template.md) file into your directory and be sure to name it
   `README.md` so it is easily viewable in the GitHub interface.
4. If you want to include images in your RFC, place them in the same
   directory as your `README.md`. 
5. Fill in the RFC. Please fill in every section in the template with as
   much detail as possible.
6. Submit a pull request to this repository with all your files. This
   begins the approval process (detailed below).
7. RFCs that are accepted will be merged directly into this repository;
   RFCs that are not accepted will have their pull request closed without
   merging.
   
## The Approval Process

When an RFC is submitted, it goes through the following process:

1.  **Initial commenting period (30 days minimum)** - the Fomantic team and
    community are invited to provide feedback on the proposal, During this
    period you should expect to update your RFC based on the feedback
    provided. Very few RFCs are ready for approval without edits, so this
    period is important for fine-tuning ideas and building consensus.
    The initial period must last at least 30 days to allow the team and
    community enough time to comment. The Fomantic team may decide to reject
    the RFC without promoting it to the next stage.
2.  **Final commenting period** (7 days) - when all feedback has been
    addressed the final commenting period will start. This is where the
    Fomantic team will provide their final feedback and either approve or
    deny the pull RFC. If they decide to deny they will provide a statement
    on why they disagree with the RFC.
3.  **Approval and Merge** - if consensus has been reached on the approval
    of the RFC the pull request will be merged. If consensus is not reached
    the pull request will be discussed in the next Fomantic team meeting to
    determine whether or not to move forward.
    
## The RFC Lifecycle

Once an RFC is merged into the repository, then the authors may implement
it and submit a pull request to the appropriate Fomantic repository without
opening an issue. Note that the implementation still needs to be reviewed
separate from the RFC, so you should expect more feedback and iteration.

If the RFC author choose not to implement the RFC, then the RFC may be
implemented by anyone. There is no guarantee that the RFCs not implemented
by their author will be implemented by the Fomantic team.

Changes to the design during implementation should be reflected by updating
the related RFC. The goal is to have RFCs to look back on to understand the
motivation and design of shipped Fomantic features.

---

**Thanks to the [ESLint](https://github.com/eslint/rfcs),
[React](https://github.com/reactjs/rfcs),
[Ember](https://github.com/emberjs/rfcs) and
[Rust](https://github.com/rust-lang/rfcs) RFC processes for their
inspiration!**
