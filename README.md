# Password
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package za.ac.cput.Password;
import org.junit.jupiter.api.AfterClass;
import org.junit.jupiter.api.AfterA;
import org.junit.jupiter.api.BeforeClass;
import org.junit.jupiter.api.BeforeA;;
import org.junit.jupiter.api.Test;
import org.junit.jupiter.api.Timeout;
import org.junit.jupiter.api.Disabled;

import static org.junit.jupiter.api.Assertions.*;

/**
 *
 * @author Cody Williams
 */
public class CodyTest {
    
    public class Cody {
    
    public Cody() {
    }
    }    
    @BeforeClass
    public static void setUpClass() {
    }
    
    @AfterA
    public static void tearDownClass() {
    }
    
    @BeforeClass
    public void setUp() {
    }
    
    @AfterClass
    public void tearDown() {
    }

    private static class Characters {

        public Characters() {
        }
    }

    private static class League {

        public League() {
        }
    }
    private static class Rank {

        public Rank() {
        }
    }
    public class TestClass {    
    private Cody Name;
    private Rank K;
    private League J;
        
    
    @BeforeClass    
 public void setUpClass(Characters Characters) {
        Name = new Cody();
        K = new Rank();
        J = new League(); 
    }    
    
  @Test
     public void objectEquality() {
        assertEquals(Name, J);
    }
     
     
      @Test
     public void objectIdentity() {
        assertEquals(Name, K);
    }
     
      @Test
     public void failingTest() {
         fail("Failed Test");
        assertEquals(Name, J);
    }
     
      @Test
      @Timeout (300)       
      public void timeoutTest() 
        throws InterruptedException {
        while (true) {
            Thread.sleep(400);
    }
      }    
   
      @Test
      @Disabled("Disabled Test")      
      public void DisableTest() {
       }
    }

 
}
