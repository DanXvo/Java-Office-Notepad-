_Hello Welcome to Java Office_

this file is file in package this app is "Nodepad java office"


>by Dannil is app in developerment

iml file:
``` iml
<?xml version="1.0" encoding="UTF-8"?>
<module type="JAVA_MODULE" version="4">
  <component name="NewModuleRootManager" inherit-compiler-output="true">
    <exclude-output />
    <content url="file://$MODULE_DIR$">
      <sourceFolder url="file://$MODULE_DIR$/src" isTestSource="false" />
    </content>
    <orderEntry type="inheritedJdk" />
    <orderEntry type="sourceFolder" forTests="false" />
  </component>
</module>
```
scroll class:
''' java

import javax.swing.JScrollPane;
import javax.swing.JTextArea;

public class Scroll extends JScrollPane {
    private String name;
    private final JTextArea text;

    public Scroll(JTextArea text, String name) {
        super(text);
        this.text = text;
    }
    public String getName(){
        return name;
    }
    public String getText() {
        return text.getText();
    }
}

'''
