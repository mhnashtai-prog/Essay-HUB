# INTUITY – Advanced Essay Mastery System

**Intuitive & Immersive Learning for B2 to C2 Level Essay Writing**

A comprehensive web application for mastering advanced essay expressions, sentence structures, and academic writing skills.

---

## 🎯 Features

### 📚 **Learn Mode**
- Interactive flashcards with 40+ key expressions
- Categories: Advantages, Disadvantages, Arguments, Balancing
- Detailed usage notes and examples
- Color-coded by expression type

### 🎯 **Practice Mode**
- Comprehensive multiple-choice exercises
- Fill-in-the-blank challenges
- Matching exercises
- Instant feedback with corrections
- Progress tracking

### 🏗️ **Sentence Structures (C1/C2)**
- 100+ advanced sentence patterns
- Participle phrases, inversions, cleft sentences
- Gerund constructions, embedded clauses
- Interactive pattern builder
- Before/after comparisons

### ✍️ **Essay Generator**
- Smart suggestion system
- Category-organized expressions
- One-click phrase insertion
- Live preview
- Export to PDF/Word/TXT

---

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd intuity-essay-master
   ```

2. **Open `index.html` in your browser**
   - No build process required
   - Works offline after first load
   - Mobile responsive

3. **Start learning!**
   - Select your level (B2 or C1/C2)
   - Choose a mode
   - Begin mastering advanced writing

---

## 📂 Project Structure

```
intuity-essay-master/
├── index.html                 # Central hub (single-page app)
├── assets/
│   ├── css/
│   │   └── style.css         # Main stylesheet
│   └── js/
│       └── app.js            # Core functionality
├── data/
│   ├── B2/
│   │   ├── advantages.json
│   │   ├── disadvantages.json
│   │   ├── arguments.json
│   │   ├── balancing.json
│   │   └── samples.json
│   └── C1-C2/
│       ├── advantages.json
│       ├── disadvantages.json
│       ├── arguments.json
│       ├── balancing.json
│       ├── structures.json    # Advanced sentence patterns
│       └── samples.json
├── modes/
│   ├── learn.html
│   ├── practice.html
│   ├── structures.html
│   └── write.html
└── README.md
```

---

## 🎨 Design Philosophy

- **Ultra-compact header** (48px) - maximum screen space for content
- **Dark theme** with beige accents (#C9A961)
- **Icon-based navigation** with tooltips
- **Smooth transitions** and animations
- **Mobile-first responsive** design

---

## 🔧 Technology Stack

- **Pure HTML/CSS/JavaScript** - no dependencies
- **Single-page application** - fast, smooth navigation
- **Local storage** - saves progress automatically
- **JSON-based content** - easy to update and maintain

---

## 📝 Content Structure

### Expression Categories (B2 & C1/C2)
1. **Introducing Advantages**
   - One of the key advantages of...
   - Makes it easier to...
   - Enables/Encourages/Helps...

2. **Introducing Disadvantages**
   - One of the disadvantages of...
   - Can lead to / Results in...
   - Prevents / Discourages / Hinders...

3. **Arguments & Criticism**
   - The main argument in favour of...
   - Proponents argue that...
   - Critics claim that...

4. **Balancing & Concluding**
   - On the one hand... On the other hand...
   - Despite the benefits...
   - Taking everything into account...

### Sentence Structures (C1/C2 Only)
1. **Participle Phrases** - Opening, mid-sentence, end position
2. **Inversion & Emphasis** - Negative inversion, emphatic forms
3. **Cleft Sentences** - It-clefts, what-clefts
4. **Gerund Constructions** - Subject and object positions
5. **Advanced Conditionals** - Inverted conditionals
6. **Embedded Clauses** - Multiple levels of subordination
7. **Nominalization** - Abstract subjects and complex nominal phrases
8. **Comparative Structures** - The more... the more...
9. **Parallel Structures** - Balanced constructions
10. **Cause-Effect Chains** - Cascading consequences

---

## 🎓 Learning Path

### B2 Level
1. Master 40+ core expressions
2. Practice with multiple-choice exercises
3. Use essay generator with guided templates
4. Build confidence with structured practice

### C1/C2 Level
1. All B2 content plus:
2. 100+ advanced sentence structures
3. Complex participle and gerund patterns
4. Inversion and cleft sentence mastery
5. Sophisticated essay construction

---

## 💾 Data Format

Example JSON structure for expressions:

```json
{
  "advantages": [
    {
      "expression": "One of the key advantages of",
      "context": "___ remote work is increased flexibility",
      "sentence": "One of the key advantages of remote work is increased flexibility.",
      "category": "advantages",
      "level": "B2",
      "usage": "Introducing the first or most important advantage",
      "variants": ["One of the main benefits of...", "A key advantage of..."]
    }
  ]
}
```

---

## 🔮 Roadmap

- [ ] Complete all JSON data files
- [ ] Embed flashcard interface in Learn mode
- [ ] Implement practice exercises
- [ ] Build sentence structure library
- [ ] Create essay generator interface
- [ ] Add export functionality (PDF/Word)
- [ ] Implement spaced repetition algorithm
- [ ] Add progress analytics dashboard
- [ ] Create sample essay library
- [ ] Add dark/light mode toggle

---

## 👨‍💻 Author

**Majid Nashtai**  
Educational Technology & Advanced Writing Instruction

---

## 📄 License

MIT License - Feel free to use for educational purposes

---

## 🙏 Acknowledgments

Built with careful attention to Cambridge English exam requirements and academic writing standards.

Special focus on distinguishing B2 proficiency from C1/C2 mastery through sophisticated sentence structures and precise expression choices.

---

## 📧 Contact & Support

For questions, suggestions, or contributions, please open an issue in the repository.

---

**Ready to master advanced essay writing? Start with `index.html`!** 🚀
