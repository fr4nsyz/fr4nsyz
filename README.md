# gweetings

I'm François, but I wish I was named Francis so the username fransys/[fr4nsyz](https://fr4nsyz.github.io/) makes more sense, but it's whateva 🫠

## Things I Got Paid To Do

- Software Engineering Intern - **IBM**

## Things I Didn't Get Paid To Do (but love doing anyways hehe)

- Open Source Contributor:
  - Cilium (Kubernetes CNI)
  - Falco (Cloud Runtime Security Framework)
- Ex AI Engineer - **Undergraduate Artificial Intelligence Society**
- Ex Security Engineer - **UofA Blueprint Chapter**

## ¬ ∃t ∈ Time : forget(t)

```cpp
int endeavor(Node* head) {
    int x = 1;
    for (Node* y = head;; y = y->next) { x *= y->data; y->prev = nullptr; if (y->next == nullptr) break; }
    return x;
}
