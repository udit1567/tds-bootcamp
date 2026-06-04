---
---

--- Before Day-3 ---
I already knew Python project management and virtual environments quite well. I have previously used uv in multiple AI, machine learning, and embedded systems projects, including projects involving different Python versions for Arduino Uno Q Edge AI development. I was already familiar with dependency management and isolated development environments.
---

## Day-3 Checklist

- [x] I can run a Python script using `uv run script.py` without setting up a local virtual environment
- [x] I know where the temporary virtual environment is created when running the `uv add --script script.py pandas` command followed by `uv run script.py`
- [x] I can create a new Python project using `uv init` and understand what `pyproject.toml` is used for
- [x] I can add a dependency (e.g., `requests`) using `uv add` and see it reflected in the lockfile
- [x] I can create a traditional virtual environment using `uv venv` and know when to use it
- [x] I understand why installing packages globally with `pip install` is a bad habit
- [x] I can open a project in VS Code, select the correct Python interpreter, and run code from the integrated terminal
- [x] I know the difference between a `.py` script and a `.ipynb` notebook, and when to use each

--- After Day-3 ---
I reinforced my understanding of uv-based workflows and learned more about how uv manages temporary environments and dependency resolution behind the scenes. The session also provided a clearer understanding of project structure using `pyproject.toml` and best practices for maintaining reproducible Python environments.
---

--- Feedback (Suggestions for the TDS Team) ---
The session was well organized and practical. Since many learners may be coming from traditional pip and venv workflows, the introduction to uv was very helpful. It would be great to include a few advanced examples showing dependency management across larger projects and multiple Python versions.
---

---
---

Personal Notes:
Already comfortable with uv and modern Python tooling. The concepts covered align closely with the workflows I use in AI, machine learning, robotics, and embedded systems projects. It was useful to see these best practices presented in a structured manner.