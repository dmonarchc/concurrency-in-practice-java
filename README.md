# Java Concurrency in Practice – Study and Examples

This repository contains a collection of examples, exercises, and notes based on the book **"Java Concurrency in Practice"** by Brian Goetz and others. The main goal is to learn and master the fundamentals of concurrent programming in Java through hands-on practice.

---

## 📘 About the Book

*"Java Concurrency in Practice"* is one of the most comprehensive and practical texts on multithreaded programming in Java. It covers topics from the basics like visibility and atomicity to high-level tools such as `ExecutorService`, `Future`, `ConcurrentHashMap`, and more.

---

## 📁 Repository Structure

The project is organized by thematic chapters. Each folder includes practical examples, explanatory notes, and tests where applicable.

```
concurrency-in-practice-java/
├── src/
│   └── main/
│       └── java/
│           ├── chapter01_thread_safety/         # Immutability, thread safety
│           ├── chapter02_sharing_objects/       # Publishing and escaping references
│           ├── chapter03_visibility_atomicity/  # Volatile, synchronization, atomicity
│           ├── chapter04_composing_objects/     # Safe composition
│           ├── chapter05_building_blocks/       # Concurrent collections, semaphores
│           ├── chapter06_task_execution/        # ExecutorService, Callable, Future
│           ├── chapter07_cancellation_interruption/ # Interruptions, task cancellation
│           ├── chapter08_thread_pools/          # Advanced thread pool configuration
│           ├── chapter09_gui_applications/      # Concurrency in GUIs
│           ├── chapter10_web_applications/      # Web applications with concurrency
│           ├── utils/                           # Shared utility classes
│           └── launcher/                        # Dummy main class for Gradle
├── build.gradle
├── settings.gradle
├── gradlew / gradlew.bat
├── gradle/
├── Makefile
└── README.md
```

---

## ⚙️ How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/concurrency-in-practice-java.git
   ```

2. Open the project in your preferred IDE (IntelliJ, VSCode, Eclipse) or use the terminal.

3. Compile the project:
   ```bash
   ./gradlew build
   ```

4. Run any example class:
   ```bash
   ./gradlew run -Pmain=chapter03_visibility_atomicity.AtomicCounter
   ```

5. (Optional) Run tests (when implemented):
   ```bash
   ./gradlew test
   ```

You can also use the provided `Makefile` to simplify some of these commands.

---

## ✅ Progress and Contributions

This repository is part of a personal study project, but feel free to open issues or pull requests if you want to contribute or add your own examples.

---

## 📚 Credits

This project is based on the concepts from the book:

**Java Concurrency in Practice**  
Brian Goetz, Tim Peierls, Joshua Bloch, Joseph Bowbeer, David Holmes, Doug Lea.  
ISBN: 0321349601

---

> ⚠️ **Note:** This repository does not include the book's text. Only examples and complementary material for educational purposes.

