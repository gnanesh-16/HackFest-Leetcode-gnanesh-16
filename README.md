---
description: >-
  This Website gives insight on Most important ones which is useful for an
  Interview at MAANG
---

# INTERVIEW Q & A

{% hint style="warning" %}
## STRINGS&#x20;
{% endhint %}



<details>

<summary><mark style="color:orange;"><strong><code>BASICS</code>                                                                </strong></mark>                                                             </summary>

1. Write a Code to Reverse a String ?

<pre class="language-java"><code class="lang-java">import java.util.Scanner;

public class ReverseString {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a string to reverse: ");
        String input = scanner.nextLine();

        String reversed = reverseString(input);
        System.out.println("Reversed string: " + reversed);
    }

    public static String reverseString(String str) {
        StringBuilder reversed = new StringBuilder();
        for (int i = str.length() - 1; i >= 0; i--) {
            reversed.append(str.charAt(i));
        }
        return reversed.toString();
    }
  }
<strong>}
</strong></code></pre>

**`Output:-`**  _`Hello World`_ \[ to ]  `dlroW olleH`&#x20;



</details>

<details>

<summary><mark style="color:orange;"><strong><code>ADVANCE</code></strong></mark>                                                               </summary>



</details>

***



{% hint style="danger" %}
Page Under Review !!
{% endhint %}
