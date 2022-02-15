 Frequency of an element
package com.ali;

import java.util.Scanner;

 class sum
	{ 
	     
	    static int count(int arr[], int n, int x) 
	    { 
	        int r = 0; 
	        for (int i=0; i<n; i++) 
	            if (x == arr[i]) 
	              r++; 
	        return r; 
	    } 
	      
	    public static void main(String args[]) 
	    { 
	        int arr[] = {1,1, 2,2,4,5,5,6,6,6,6,9,10,11}; 
	        int n = arr.length; 
	        int x = 6; 
	        System.out.println(count(arr, n, x)); 
	    } 
	} 
