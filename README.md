# LinkedList

//we are creating linked list with the help of node.
class Node {
    int data;
    Node next;
    public Node(int data) {
        this.data = data;
        this.next = null; [//at starting we are assuming that the node is not pointing any other node]
    }
}