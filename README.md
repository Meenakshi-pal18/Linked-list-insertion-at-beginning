# Linked-list-insertion-at-beginning
class Solution {
  public:
    Node *insertAtFront(Node *head, int x) {
        // Code here
        Node* temp;
        temp=new Node(x);
        temp->next=head;
        head=temp;
        return head;
    }
};
