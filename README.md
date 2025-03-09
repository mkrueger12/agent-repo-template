# 🤖 Agentic Systems Organization

## 👋 About

This repository is an opinionated take on how to organize you agentic systems. Agentic systems will continue to increase in complexity.
In order to effectively build and manage these systems, we need to organize our work effciently. Here are my latest thoughts on how to accomplish this.

## 🧠 Agents
- Most agent coding frameworks have an ```Agent``` class. Place those here.
- They can all be uniqiue ```.py``` files or contained in one file.

## 📝 Instructions
- All your prompts go here.
- Commonly these are ```.txt```, ```.py```, or ```.yaml``` files.
- Instructions can then be dynamically generated for your agents.

## 🔧 Tools
- Any function that you may want your agents to use should be stored in tools.
- This also includes any utility functions you write for your own operations.

## 📦 Artifacts
- Any data that was created by an agent and needs to be consumed by another agent should be stored in artifacts.
- As your project scales, this may need to be stored in a database or other data store.

## 🧪 Tests
- Any tests for your project should be stored in the tests folder.
- Open question: What is the the optimal way to test your agentic systems?

## 🤝 Contributions
- Contributions are welcome! Please open a PR or issue if you have any suggestions or feedback.
