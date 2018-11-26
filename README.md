# Portfolio
*epic* and also *g*

also ok thanks.


m̋͑̋́̈́̾ͪͬ̅ͧ͛̽̓̄ͤͩ̔͂̚͏̡̰̼͍͙͡y͔̥̣̖̘̘̦͓̟͈̖̥͆ͩ̓͋͊͋̉̋̏̾ͫͥ̚͠ ̴̖͔͓̫̬ͮ̒̌̓̈́ͬ̍ͮ̽̏ͧͯ́͡ͅn̶͉̩̪͙̲̻̙͎̠̜͐͆̌̒͢͠ͅͅa̢̡̤̦͇͕ͦ̀̉̉̍̒͑̓͊̂́͢͝m̦̘̟͎̯̫̜̲̲̹̖͇̖̣͈̲̭ͣ̽́̉͐̄͊͠é̛̛͇̰͔̙̲͍̥̯̙̽͑̅͆͐͑̒̇ͦ͐̄̚̚͘͘͞ ̶̽̿̒ͨ͊ͫͫ̄͑̽̀̌͜͏̤̥̫̗͔̪̖̭̮̝̙̪̖̩̹͚̰̬ì̷̭͈̳̱ͮͬ̔́͒ͧͮ̇̑̕ş̵̷̙̭͉͙̯͕̜̘ͣ́ͨ̍̅̏͟͝ ̧̟̙͖͔̗̯̙̭ͥͨ͛͌͐ͦ͊ͤ̂̄ͬ̀͘ͅĵ̷̵̴̪̻͈̹͖͓̒̏͂̅̇̍̓͢ͅȩ̛ͧ͋͗ͮ̅̓̆̿̄̅ͮ̓̒̓ͭͬͮ̐́͟҉̤͎̮͍̞͕̹͙̬̠f̛̛̳̜̥̝̮͚̜͕̼̩̻̗ͨ̊ͫͪͦ̂͋̃ͤ̏̒͜f̸̛̝̹̼͔͖͔̫̦̠͔̞̹̙̙͙̎ͮͨ̓̀

---

# Reflection


Most of the pride I have as a programmer come from outside of class. Here are a few:

My most recent project is my C# library, [RazorSharp](https://github.com/Decimation/RazorSharp).

I also wrote a [few articles](https://www.codeproject.com/Articles/1254217/Calculating-Heap-Size-of-Managed-Objects) on the code I wrote documenting .NET internals.

This specific code snippet uses pointer manipulation and pointer arithmetic which helped me understand pointers.

```C#
[MethodImpl(MethodImplOptions.AggressiveInlining)]
		public static Pointer<byte> AddressOfHeap<T>(ref T t) where T : class
		{
			TypedReference tr = __makeref(t);

			// NOTE:
			// Strings have their data offset by RuntimeHelpers.OffsetToStringData
			// Arrays have their data offset by IntPtr.Size * 2 bytes (may be different for 32 bit)
			return **(IntPtr**) (&tr);
		}
```       

Around April 2018, I started writing my C triangle solver for the TI-84: [TITrig](https://github.com/Decimation/TITrig). This project taught me a lot about assembly, specifically Zilog Z80 assembly, and native programming.

My first significant project was my [Cydia repository](https://github.com/Decimation/decimation.github.io) for jailbroken iOS devices which I made in 8th grade. It has served as a template for many GitHub-based Debian APT package management repositories.

For my class-based accomplishments, I learned a lot about Processing (which I honestly dislike) and drawing methods. It has helped me visually channel my creativity.

---

# Most difficult code
[This entire file](https://github.com/Decimation/TITrig/blob/master/src/Right/RightTriangle.c)

My "most difficult" code from <a href="https://github.com/StantonR16/starfield5">Starfield</a>:

```Java
void move(double angleDelta) {
    m_color = color((int)(Math.cos(m_angle) * 255),(int)(Math.sin(m_angle) * 255),(int)(Math.tan(m_angle) * 255));
    m_x = Math.cos(m_angle) * m_scalar + (m_x);
    m_y = Math.sin(m_angle) * m_scalar + (m_y);
    m_angle += angleDelta;
  }
```

Basically, this code does some epic trigonometric and sinusoidal calculations which move the star. This code actually wasn't hard at all (because SOH-CAH-TOA is epic), but relatively speaking it was hard to visualize the calculations.

---

# My favorite languages

1. `C#`
2. `C++`
3. `Java`
4. `C`

---

# Links

<p></p>


<details><summary><strong>TI-84 Triangle solver written in C</strong></summary>
<p>

<a href="https://github.com/Decimation/TITrig">TITrig<br></a>

<p>45-45-90<br> <img src="https://raw.githubusercontent.com/Decimation/TITrig/master/45_45_90.png"></p>

<p>AAS<br> <img src="https://raw.githubusercontent.com/Decimation/TITrig/master/aas.png"></p>

</p>
</details>

<p></p>

<details><summary><strong>Chemotaxis</strong></summary>
<p>

<a href="https://github.com/StantonR16/Chemotaxis">Chemotaxis<br></a>

<a href="https://stantonr16.github.io/Chemotaxis/">Chemotaxis URL</a>

</p>
</details>

<p></p>


<details><summary><strong>Dice</strong></summary>
<p>

<a href="https://github.com/StantonR16/Dice">Dice<br></a>

<a href="https://stantonr16.github.io/Dice/">Dice URL</a>

</p>
</details>

<p></p>


<details><summary><strong>Lightning</strong></summary>
<p>

<a href="https://github.com/StantonR16/lightning2">Lightning (+JS)<br></a>

<a href="https://stantonr16.github.io/lightning2/">Lightning URL<br></a>

<!-- <a href="https://stantonr16.github.io/Dice/">Lightning JS</a> -->

</p>
</details>

<p></p>


<details><summary><strong>Web page</strong></summary>
<p>
  
  <a href="https://github.com/StantonR16/TestPage">Web page<br></a>
  
  <a href="https://stantonr16.github.io/TestPage/">Web page URL<br></a>


</p>

</details>

<p></p>

<details><summary><strong>College presentation</strong></summary>

<p>
  
  <a href="https://docs.google.com/presentation/d/10J8a6gS9GdSibj7b8eD5rL5nlw0OKGnh99JgMz0yQVU/edit?usp=sharing">Presentation<br></a>


</p>
</details>
<p></p>

<details><summary><strong>Starfield</strong></summary>

<p>
  
  <a href="https://github.com/StantonR16/starfield5">Starfield<br></a>
  
  <a href="https://stantonr16.github.io/starfield5/">Starfield URL<br></a>


</p>
</details>
