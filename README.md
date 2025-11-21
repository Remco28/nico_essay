# Essay Critique Tool

An AI-powered essay critique system designed to help middle and high school students improve their writing. This tool generates teacher-style feedback with visual markup in an easy-to-read HTML format.

## 🎯 Who Is This For?

- **Students** who want constructive feedback on their essays
- **Parents** helping their children improve their writing
- **Anyone** looking for detailed, grade-appropriate essay critiques

## ✨ Features

- **Visual feedback** with color-coded comments (strengths, suggestions, areas for improvement)
- **Inline edits** with strikethrough and replacement suggestions
- **Grade assessments** across multiple criteria
- **Teacher-style tone** that's encouraging but constructive
- **HTML output** that works in any web browser - no special software needed

## 📁 Project Structure

```
your-project/
├── essay_assignment_1/
│   ├── assignment.md          # (Optional) The assignment instructions/rubric
│   ├── draft1.md              # Your essay draft
│   └── draft1_critique.html   # Generated critique (created by AI)
├── essay_assignment_2/
│   ├── rubric.txt
│   ├── draft1.md
│   └── draft1_critique.html
└── ...
```

## 🚀 How to Use

### Step 1: Set Up Your Essay Folder

Create a new folder for each essay assignment. Inside that folder:

1. **Add your essay draft** (can be `.md`, `.txt`, or any text format)
2. **Add assignment instructions** (optional but helpful) - include the prompt, rubric, or any criteria your teacher provided

Example:
```
essay_project_1/
├── assignment.txt
└── my_essay.md
```

### Step 2: Start Your AI Agent

Use any AI assistant that can read files and generate HTML (Claude, ChatGPT, etc.).

### Step 3: Load the Instructions

Tell the AI agent:
```
Please read the agent_instructions.md file from the Essay Critique Tool repository
and help me critique my essay.
```

Or provide this URL: `https://github.com/[your-username]/[repo-name]/blob/main/agent_instructions.md`

### Step 4: Answer the Prompts

The AI will ask you for:
- **Grade level** (e.g., "8th grade" or "11th grade")
- **Location of your essay file**
- **Location of assignment/rubric** (if you have one)
- **Any specific concerns** (optional - e.g., "I'm worried about my conclusion")

### Step 5: Review Your Critique

The AI will generate an HTML file (e.g., `my_essay_critique.html`) in your essay folder. Open it in any web browser to see:

- 📊 Overall grade assessment
- ✅ Strengths highlighted in green
- 💡 Suggestions in blue
- ✏️ Teacher comments in yellow
- ✂️ Inline edits with strikethrough and replacements

### Step 6: Revise and Repeat

After revising your essay:
1. Save the new version as `draft2.md` (or similar)
2. Run the critique process again
3. Compare `draft1_critique.html` and `draft2_critique.html` to see your improvement!

## 📋 Tips for Best Results

- **Be honest about grade level** - The feedback is tailored to what's appropriate for your age
- **Include the assignment instructions** - This helps the AI understand what you're trying to accomplish
- **Ask specific questions** - If you're worried about something specific, mention it
- **Use this iteratively** - Critique draft 1, revise, critique draft 2, etc.

## 🎨 What the Critique Looks Like

The HTML critique includes:

- **Grade Box**: Overall assessment with scores for thesis, evidence, organization, mechanics
- **Paragraph-by-Paragraph Feedback**: Each section of your essay is analyzed
- **Color-Coded Comments**:
  - 🟢 Green boxes highlight what you're doing well
  - 🟡 Yellow boxes provide teacher comments
  - 🔵 Blue boxes offer specific suggestions
- **Inline Edits**: See exactly what could be improved with strikethrough and suggested replacements
- **Final Thoughts**: Summary of strengths and next steps

## 📖 Example

See `example/essay1.md` and `example/essay1_critique.html` for a complete example of an 8th-grade essay and its critique.

## 🤝 Contributing

Found a bug? Have suggestions for improvement? Feel free to open an issue or submit a pull request!

## 📄 License

This project is open source and available under the MIT License.

## ❓ FAQ

**Q: Do I need to know how to code?**
A: Nope! Just create folders, save text files, and use an AI assistant.

**Q: What AI assistants work with this?**
A: Any AI that can read files and generate HTML - Claude, ChatGPT, and similar tools.

**Q: Can teachers use this?**
A: Absolutely! It's designed to augment (not replace) teacher feedback.

**Q: Will the AI just write my essay for me?**
A: No - this tool only critiques existing essays. You still do all the writing!

**Q: What if I don't have the assignment instructions?**
A: That's okay! The AI will still provide feedback based on general essay-writing best practices for your grade level.

## 🔗 Related Files

- [`agent_instructions.md`](agent_instructions.md) - Instructions for AI agents
- [`template_reference.html`](template_reference.html) - HTML template reference

---

**Happy writing! 📝**
