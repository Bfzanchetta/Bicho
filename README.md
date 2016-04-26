package bicho;

import java.util.NoSuchElementException;
import javax.xml.soap.Node;

/**
 *
 * @author aluno
 */
public class BST{
    
    private Node root;
    
    private class Node{
        //Cada nodo tem uma equacao de reta, ou ponto inicial e final//
        //Tambem tem uma normal//
        private double xiDaReta, xfDaReta, yiDaReta, yfDaReta;
        private double xiDaNormal, xfDaNormal, yiDaNormal, yfDaNormal;
        private Node left;
        private Node right;
        private int N;  //index do nodo

        public Node(double xiDaReta, double xfDaReta, double yiDaReta, double yfDaReta, double xiDaNormal, double xfDaNormal, double yiDaNormal, double yfDaNormal, Node left, Node right, int N) {
            this.xiDaReta = xiDaReta;
            this.xfDaReta = xfDaReta;
            this.yiDaReta = yiDaReta;
            this.yfDaReta = yfDaReta;
            this.xiDaNormal = xiDaNormal;
            this.xfDaNormal = xfDaNormal;
            this.yiDaNormal = yiDaNormal;
            this.yfDaNormal = yfDaNormal;
            this.left = left;
            this.right = right;
            this.N = N;
        }
    }
    
    public boolean isEmpty(){
        if(isEmpty())
            return true;
        else return false;
    }
    
    
    
}
