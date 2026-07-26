## gweetings

I'm François, but I wish I was named Francis so the username fransys/[fr4nsyz](https://fr4nsyz.github.io/) makes more sense, but it's whateva 🫠

## Experience

- Software Engineering Intern - **IBM**
- Ex AI Engineer - **Undergraduate Artificial Intelligence Society**
- Ex Security Engineer - **UofA Blueprint Chapter**

## ¬ ∃t ∈ Time : forget(t)

```cpp
int endeavor(Node* head) {
    int x = 1;
    for (Node* y = head;; y = y->next) { x *= y->data; y->prev = nullptr; if (y->next == nullptr) break; }
    return x;
}
