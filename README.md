# Smart-Home Agent Learning

This repository demonstrates Git and GitHub skills using a smart-home
agent evaluation notebook related to my Honours project.

## Why this repository was created

I created this repository from scratch as a dedicated artefact to
showcase what I learned from the freeCodeCamp Git and GitHub course.

The repository I originally used while completing the course was later
used for other activities and testing. It was therefore no longer a
suitable, focused artefact to share for this activity.

This repository records a fresh application of the skills I learned.
Its commit history represents this demonstration, rather than the
original course practice sessions.

## Project

The notebook evaluates a language model that routes household command
transcripts to simulated device-control, state-query or clarification
operations.

It compares a basic prompt with a prompt containing explicit rules
and development examples.

## Scope

The project uses text transcripts and simulated devices.
Results apply to the examples evaluated in the notebook.

## How to run

1. Open notebooks/ai_evaluation_test.ipynb in Google Colab.
2. Select a T4 GPU runtime.
3. Run the cells in order.
4. Inspect the development checks before the full evaluation.
5. Review the comparison table, charts and execution traces.

The first cell installs dependencies. The model is downloaded during
setup. Inference then runs within the notebook runtime.

## Evaluation measures

- Schema validity checks whether the generated decision follows the schema.
- Routing accuracy checks whether control, query or clarify was selected correctly.
- Complete task success checks the decision, tool calls, output and final state.
- Incorrect control calls count control operations on requests labelled for clarification.

Each request starts with the same initial simulated device states.
