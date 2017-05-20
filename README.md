# CollectionsSet
package com.company;

import java.util.*;
public class Collections {
    public static void main(String[] args) {
        // Create the sorted set
        SortedSet set = new TreeSet();

        // Add elements to the set
        set.add("lettuce");
        set.add("spinach");
        set.add("broccoli");
        set.add("sprouts");
        set.add("bell peppers");
        set.add("kale");
        set.add("carrots");


        // Iterating over the elements in the set
        Iterator it = set.iterator();

        while (it.hasNext()) {
            // Get element
            Object element = it.next();
            System.out.println(element.toString());
        }

    }
}
