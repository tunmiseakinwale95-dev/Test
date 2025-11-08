# OCR A Level Computer Science Flashcards

Comprehensive flashcard collection for OCR A Level Computer Science Units 1 & 2

## 📚 What's Included

### Unit 1: Computer Systems (175 flashcards)
- Computer Components & Architecture
- Fetch-Decode-Execute Cycle
- Processor Types & Architecture
- Input, Output & Storage Devices
- Operating Systems & Scheduling
- Networking Fundamentals
- Data Types & Representation
- Images & Sound Representation
- Software Development
- Legal, Moral, Ethical & Cultural Issues
- Boolean Algebra & Logic
- Data Structures
- Algorithms

### Unit 2: Algorithms and Programming (208 flashcards)
- Computational Thinking
- Programming Fundamentals
- Recursion
- Abstract Data Types
- Binary Trees
- Graphs
- Object-Oriented Programming
- Algorithm Efficiency & Big O
- Sorting Algorithms
- Searching Algorithms
- File Handling
- Exception Handling
- SQL & Databases
- Dictionaries & Hash Tables
- Algorithm Design Techniques
- Arrays, Lists & Tuples
- Notation & Expressions

**Total: 383 flashcards**

## 📁 File Formats

### For Digital Study:
- **`cs-alevel-unit1-flashcards.json`** - Unit 1 in JSON format
- **`cs-alevel-unit2-flashcards.json`** - Unit 2 in JSON format
- **`FLASHCARDS.md`** - Combined markdown reference (both units)

### For Quizlet Import:
- **`quizlet-import-unit2.txt`** - Ready to import into Quizlet (Unit 2)

### Documentation:
- **`OCR-UNIT2-COVERAGE.md`** - Complete specification coverage checklist
- **`README.md`** - This file

## 🚀 Quick Start

### Option 1: Import to Quizlet

1. Go to [Quizlet.com](https://quizlet.com) and create an account
2. Click "Create" → "Study set"
3. Click "Import"
4. Select custom format with:
   - Between term and definition: **Tab**
   - Between cards: **New line**
5. Copy contents of `quizlet-import-unit2.txt` and paste
6. Click "Import" then "Create"

### Option 2: Print Study Guide

1. Open `FLASHCARDS.md` in any markdown viewer
2. Export to PDF using your browser or a markdown tool
3. Print for physical study

### Option 3: Build Your Own App

Use the JSON files to create custom flashcard apps or quizzes:

```javascript
// Example: Load flashcards in JavaScript
fetch('cs-alevel-unit2-flashcards.json')
  .then(response => response.json())
  .then(data => {
    console.log(`Loaded ${data.total_flashcards} flashcards`);
    data.categories.forEach(category => {
      console.log(`${category.name}: ${category.flashcards.length} cards`);
    });
  });
```

```python
# Example: Load flashcards in Python
import json

with open('cs-alevel-unit2-flashcards.json', 'r') as f:
    data = json.load(f)
    print(f"Loaded {data['total_flashcards']} flashcards")
    for category in data['categories']:
        print(f"{category['name']}: {len(category['flashcards'])} cards")
```

## 📖 Study Methods

### Active Recall
1. Read question
2. Try to answer without looking
3. Check answer
4. Mark if correct/incorrect
5. Review incorrect answers later

### Spaced Repetition
- Day 1: Study new cards
- Day 2: Review Day 1 cards
- Day 4: Review Day 1 cards again
- Day 7: Review Day 1 cards
- Day 14: Final review

### Categorized Study
Focus on one category at a time:
- Day 1: Computational Thinking + Programming Fundamentals
- Day 2: Recursion + Abstract Data Types
- Day 3: Trees + Graphs
- Day 4: OOP + Algorithm Efficiency
- Day 5: Sorting + Searching
- Day 6: Files + Exceptions + SQL
- Day 7: Review all

## ✅ Specification Coverage

### Unit 2 Coverage (H446/02):
- ✅ 2.1 Elements of Computational Thinking
- ✅ 2.2 Problem Solving and Programming
- ✅ 2.3 Algorithms
- ✅ 2.4 Data Types and Structures
- ✅ 2.5 Object-Oriented Programming (if applicable)
- ✅ 2.6 File Handling
- ✅ 2.7 Exception Handling
- ✅ 2.8 Databases and SQL
- ✅ All standard algorithms (sorting, searching, traversals)
- ✅ All data structures (stacks, queues, trees, graphs, hash tables)
- ✅ Notation (infix, prefix, postfix/RPN)

See `OCR-UNIT2-COVERAGE.md` for detailed checklist.

## 🎯 Exam Tips

### Before the Exam:
1. Complete all flashcards at least twice
2. Practice past papers (OCR H446/02)
3. Implement algorithms in code
4. Draw diagrams for data structures
5. Practice SQL queries
6. Trace algorithms with sample data

### During the Exam:
1. Read questions carefully
2. Show working for algorithm analysis
3. Use pseudocode unless code specified
4. Draw diagrams where helpful
5. Check Big O answers
6. Verify SQL syntax

### Common Mistakes to Avoid:
- ❌ Confusing O(log n) with O(n)
- ❌ Forgetting base cases in recursion
- ❌ Mixing up DFS and BFS
- ❌ Wrong SQL JOIN syntax
- ❌ Confusing pass by value/reference
- ❌ Incorrect tree traversal order

## 🛠️ Customization

### Adding Your Own Flashcards:

**JSON Format:**
```json
{
  "question": "Your question here",
  "answer": "Your answer here"
}
```

Add to appropriate category in the JSON file.

**Quizlet Import Format:**
```
Your question here[TAB]Your answer here
```

Add to new line in the txt file.

## 📊 Progress Tracking

Create a checklist:

```markdown
### Unit 2 Progress

#### Category 1: Computational Thinking (6 cards)
- [ ] First pass
- [ ] Second pass
- [ ] Mastered

#### Category 2: Programming Fundamentals (10 cards)
- [ ] First pass
- [ ] Second pass
- [ ] Mastered

... (continue for all categories)
```

## 🤝 Contributing

Found an error or want to add more flashcards?

1. Fork the repository
2. Make your changes
3. Submit a pull request

Or simply open an issue with suggestions.

## 📜 License

These flashcards are created for educational purposes for OCR A Level Computer Science students.

## 🎓 Additional Resources

### Official OCR Resources:
- [OCR A Level Computer Science Specification](https://www.ocr.org.uk/qualifications/as-and-a-level/computer-science-h046-h446-from-2015/)
- OCR Past Papers and Mark Schemes
- OCR Specimen Assessment Materials

### Recommended Practice:
- Implement all algorithms in your chosen language (Python, Java, C#)
- Practice SQL on [SQLite Online](https://sqliteonline.com/)
- Use [VisuAlgo](https://visualgo.net/) for algorithm visualization
- Practice tree traversals on paper

### Textbooks:
- OCR A Level Computer Science by P.M. Heathcote
- A Level Computer Science for OCR by Bond & Langfield

## 📞 Support

Questions or issues?
- Check `OCR-UNIT2-COVERAGE.md` for specification mapping
- Review `FLASHCARDS.md` for detailed explanations
- Consult your teacher or tutor
- Practice with past papers

---

**Good luck with your exams! 🎓**

*Study smart, not just hard*
