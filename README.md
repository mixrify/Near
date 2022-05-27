# <img src="https://media.discordapp.net/attachments/916226674071339010/978708607426244608/JovanaScriptBanner.png" width="300" height="100" alt="#">

JovanaScript, an object oriented programming language that uses the CSC & JOVS compiler and embeds into the JovanaScript Text Editor. It currently supports ConsoleApps, WinApps and Application Extension (DLL) Creation.

## How it works

<img src="https://media.discordapp.net/attachments/916226674071339010/979739362851975188/unknown.png" alt="#">

When writing an application with the text editor, you are able to use JovanaScript **and C#**, considering we also use the CSC compiler. However, C# is not entirely supported on the Text Editor nor recommended unless needed. If you're curious of how JovanaScript works, check out the [JovanaScript Documentation](/#).

When decompiling a JovanaScript-written application, the source code will appear with the **C# language**—To avoid that, the only way is **obfuscating** your application, which is possible **on JovanaScript**.

# How to obfuscate a JovanaScript-written application

Obfuscating a JovanaScript application is easy, as it is possible to do it **inside the code of your application**. Impressive, right? Well, here's how to do it:

~ **Obfuscation code example**

```csharp
import (Packages.reg);
import (Packages.jov.obf);

namespace Obfuscator {
    
    class veryCoolObfuscator {
        
        static void Main(string[] arguments) {
            
            
            printJ("Obfuscated application open!");
            printJ.PauseAtKey();
            
            
        }
        
        protected visoFunc void Obfuscate { // This part of the code will not be visible after decompiling since it has used the visoFunc method to automatically run and get removed.
            
            foreach (Option in this.ObfuscatorOptions) {
                
                var myObf = new JovanaObfuscator("stringObf"); // Select the Obfuscation Methods (e.g. stringObf, metaObf, relocator, config4, garbage, antidebug, dnspykill)
                
                myObf.Obfuscate(this);
                
                
            }
        }
        
    }
    
}
```

Using the code above tells the JOVS compiler to remove the [visoFunc](/#) void and then obfuscate the app after removing the void & after the app finishes being compiled.

## Contribution

Current contributors: Pronner
If you'd like to contribute, please fork the repository, add/remove or just change whatever you think should be changed and then submit a pull request.

## Sneak peeks of the Text Editor & Language

<img src="https://media.discordapp.net/attachments/940575794110038017/979729931657416754/unknown.png?width=918&height=473" alt="#">

 -> Updates and more

- [ ] Two supported compilers for the Text Editor (JOVS & CSC)
- [ ] Application Build
- [ ] Console Apps
- [ ] Win Apps
- [ ] App Extensions Development
- [ ] App Icon customization
- [ ] Tutorials for JovanaScript
- [ ] Script saving & sharing
- [ ] Git support

That's it for now!
