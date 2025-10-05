# 📝 Note Generation Template

Using the rules, persona, and exact structure defined in @agents.md, create comprehensive notes for the following topic.

---

## 🎯 Required Information

**Topic:**
[Write your main topic here - e.g., "Machine Learning Basics", "Docker Containers", "Project Management"]

---

## 📚 Source(s)

**Primary Source(s):**
- [Add your main source(s) here - video URLs, article links, documentation, etc.]
- [For videos, include YouTube/Vimeo links]
- [For articles, include URLs]
- [For books, include title and chapter/page numbers]

**Additional Context:**
[Optional: Add any specific topics, subtopics, or focus areas you want covered. For example:
- "Cover topics: X, Y, Z"
- "Focus on practical applications for developers"
- "Explain from a beginner's perspective"
- "Include code examples in Python"]

---

## ⚙️ Configuration (Optional)

**Target Audience:**
[Leave blank for general audience, or specify: developers, managers, students, beginners, etc.]

**Depth Level:**
[Choose one: Beginner | Intermediate | Expert]
Default: Intermediate

**Special Requirements:**
[Optional: Any other specific requests like "focus on real-world examples", "include more diagrams", etc.]

---

## 💾 Output

**Save As:**
@[YourTopicName.md]

---

# 📋 Example Templates

## Example 1: Video Source
```
**Topic:** Kubernetes Architecture

**Primary Source(s):**
- https://www.youtube.com/watch?v=example123

**Additional Context:**
Cover all topics mentioned in the video: Pods, Services, Deployments, ConfigMaps, and Secrets

**Target Audience:** Backend developers

**Depth Level:** Intermediate

**Save As:** @[Kubernetes_Architecture.md]
```

## Example 2: Multiple Sources
```
**Topic:** GraphQL vs REST APIs

**Primary Source(s):**
- https://graphql.org/learn/
- https://www.howtographql.com/basics/1-graphql-is-the-better-rest/
- https://www.youtube.com/watch?v=example456

**Additional Context:**
Compare and contrast both approaches, include performance considerations

**Target Audience:** Full-stack developers

**Depth Level:** Expert

**Save As:** @[GraphQL_vs_REST.md]
```

## Example 3: Beginner-Friendly
```
**Topic:** Git Basics

**Primary Source(s):**
- https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control

**Additional Context:**
Focus on everyday commands: clone, commit, push, pull, branch, merge. 
Use simple everyday analogies.

**Target Audience:** Complete beginners with no version control experience

**Depth Level:** Beginner

**Save As:** @[Git_Basics.md]
```

## Example 4: Concept Deep Dive
```
**Topic:** Event-Driven Architecture

**Additional Context:**
No specific source - synthesize from your knowledge and web research.
Cover: event sourcing, CQRS, message brokers, pub-sub patterns, eventual consistency

**Target Audience:** Senior software architects

**Depth Level:** Expert

**Save As:** @[Event_Driven_Architecture.md]
```

---

# 🚀 Quick Start Template (Copy & Paste)

```
Using the rules, persona, and exact structure defined in @agents.md, create comprehensive notes for the following topic.

**Topic:**
[Your topic here]

**Primary Source(s):**
- [Your source URL or reference]

**Additional Context:**
[Any specific requirements or focus areas]

**Target Audience:**
[Your target audience or leave blank]

**Depth Level:**
[Beginner | Intermediate | Expert]

**Save As:**
@[YourFileName.md]
```

---

## 💡 Tips for Best Results

1. **For Video Sources:** 
   - Cognito will create a Topic Coverage Map with timestamps
   - All topics mentioned will be comprehensively covered
   - Examples and demonstrations will be captured

2. **For Multiple Topics:** 
   - List all subtopics in "Additional Context"
   - Cognito will ensure complete coverage

3. **For Specific Audiences:** 
   - Always specify your target audience for tailored vocabulary and examples

4. **For Complex Topics:** 
   - Consider using "Expert" depth level
   - Request specific aspects you want emphasized

5. **File Naming:** 
   - Use descriptive names with underscores: `Topic_Name.md`
   - Avoid spaces in filenames