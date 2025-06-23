# Instructions for Writing a Commit Message (Semantic Style)

Follow these steps to generate a clear, useful, and conventional commit message.
Use the semantic commit format to improve collaboration, changelog generation,
and codebase clarity. Return the message as is without any additional formatting
or context. Dot not wrap message in code block markdown.

## Format

```
<type>: <subject>

<body>
```

- `<type>`: the category of the change.
- `<subject>`: a short summary of the change in present tense.
- `<body>`: a more detailed commit, with additional information on the why. Add
  only information provided by the context, do not invent any why or how without
  clear instruction. (OPTIONAL)

## Rules

- Separate subject from body with a blank line
- Limit the subject line to 50 characters
- Capitalize the subject line
- Do not end the subject line with a period
- Use the imperative mood in the subject line
- Wrap the body at 72 characters
- Use the body to explain what and why vs. how
- The body is only required if the reason is not immediately obvious but is
  important. Minor style changes likely don't need a body for example

## Information

Following this section you will receive additional information to construct this
message

The Context will provide additional qualitative information on the change,
include ALL this information in message you generate. Reformat to improve
grammar, spelling and understanding.

The Commit type present `<type>: <type description>`. Quote the <type> directly
in the subject line. Use the description to add additional context if required.

Staged Changes include all the changes that will be added to the commit as given
by the command `git diff --staged`

## Additional Information:

