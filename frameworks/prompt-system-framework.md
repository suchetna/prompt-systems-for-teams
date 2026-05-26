# Prompt System Framework

This framework helps teams move from one-off prompts to reusable prompt systems that support real work.

## 1. Define the task

Questions:
- What is the prompt meant to help with?
- Which workflow does it support?
- What kind of output is needed?

Strong signals:
- The task is specific
- The output is useful
- The prompt supports a real team need

## 2. Define the inputs

Questions:
- What information does the model need?
- Which inputs are required every time?
- What context should be provided explicitly?

Strong signals:
- Inputs are clear
- Placeholders are easy to use
- The prompt does not rely on hidden context

## 3. Structure the instructions

Questions:
- What should the model do?
- What tone, format, or audience should it follow?
- What should it avoid?

Strong signals:
- Instructions are clear
- Constraints are visible
- Output structure is explicit

## 4. Add guardrails

Questions:
- Should the model avoid making unsupported claims?
- Should it ask for clarification when context is missing?
- Does the output require human review?

Strong signals:
- Limits are stated
- Risky behavior is reduced
- Review expectations are clear

## 5. Test and improve

Questions:
- Has the prompt been tested with varied examples?
- What kinds of failure modes appear?
- How will improved versions be saved and shared?

Strong signals:
- Testing is documented
- Good versions are easy to find
- The team can keep improving the prompt
