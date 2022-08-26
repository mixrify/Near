# <img src="https://media.discordapp.net/attachments/916226674071339010/1006652155790372884/Near_2.png?width=473&height=473" width="200" height="200" alt="#">

Near, a modern object-oriented programming language that uses the CSC & JOVS compilers and embeds into the Near Text Editor. It currently supports **ConsoleApps**, **WinApps** and **Application Extension (DLL)** Creation. 

Near was first developed at **5/24/2022**, aiming to create another family language of **C** which compiles into C# code using the JOVS & CSC compilers.

## How it works

<img src="https://media.discordapp.net/attachments/980517878220615710/992873450521772062/unknown.png" alt="#">

When writing an application with the text editor, you are able to use Near **and C#**, considering we also use the CSC compiler. However, C# is not entirely supported on the Text Editor nor recommended unless needed. If you're curious of how Near works, check out the [Near Documentation](/#).

When decompiling a Near-written application, the source code will appear with the **C# language**—To avoid that, the only way is **obfuscating** your application, which is possible **on Near**.

# How to obfuscate a Near-written application

Obfuscating a Near application is easy, as it is possible to do it **inside the code of your application**. Impressive, right? Well, here's how to do it:

~ **Obfuscation code example**

```csharp
#import Packages.reg;
#import Packages.near.obf;

namespace Obfuscator {
    
    class veryCoolObfuscator {
        
        static -> void Main(string[] arguments) {
            
            
            printN("Obfuscated application open!");
            printN.PauseAtKey();
            
            
        }
        
        protected visoFunc -> void Obfuscate { // This part of the code will not be visible after decompiling since it has used the visoFunc method to automatically run and get removed.
            
            foreach (Option in this.ObfuscatorOptions) {
                
                var myObf = new NearObfuscator("stringObf"); // Select the Obfuscation Methods (e.g. stringObf, metaObf, relocator, config4, garbage, antidebug, dnspykill)
                
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

## Sneak peeks of the IDE & Language

<img src="https://media.discordapp.net/attachments/916226674071339010/1012664192177803284/unknown.png?width=888&height=473" alt="#">
<img src="https://media.discordapp.net/attachments/916226674071339010/1012664316123697222/unknown.png?width=890&height=473" alt="#">

 # Updates and more
 Here are the updates of the language & IDE.

- [x] Two supported compilers for the Text Editor (JOVS & CSC)
- [x] Application Build
- [x] Console Apps
- [x] Win Apps
- [x] App Extensions Development
- [x] App Icon customization
- [x] Tutorials for JovanaScript
- [x] Script saving & sharing
- [ ] Git support
- [x] Controls (Undo, Redo, Run Application, etc)
- [x] Error Indicator
- [x] Project Settings
- [x] Ability to open files with Near (ex. opening a .near file with Nearify IDE)
- [x] Support of multiple files (BETA, may be buggy)
- [x] Advnaced definitions & Arrays support

# Support us

Want to help us out? Check out our [ko-fi page](https://ko-fi.com/JovanaScript)! We currently support direct payments only, we do not support crypto payments yet so this is the only option as of now.

Thank you for your support ♥

# Licensing

Near (the language source) is licensed with [**GNU Lesser General Public License v2.1**](https://github.com/Pronner/JovanaScript/blob/main/LICENSE), while the name is licensed with a **Trademark**.

-> Source permissions:

- [x] Commercial use [✔] **[NOT RECOMMENDED]**
- [x] Modification [✔]
- [x] Distribution [✔]
- [x] Private use [✔]
- [ ] Liability [❌]
- [ ] Warranty [❌]

-> Source conditions:

- [x] License and copyright notice **[MUST]**
- [x] Disclose source **[MUST]**
- [x] State changes **[MUST]**
- [x] Same license (library) **[MUST]**

If you do not abide to the conditions or if you cross the permissions allowed you will face consequences privately once caught.
Thank you.
