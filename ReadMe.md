# KEML Edit

This project holds edit code for KEML files.
It can be generated in a basic flavor from [keml](https://gitlab.uni-koblenz.de/keml/keml). However, this version is advanced in the sense that it has custom icons that are used conditionally.

## Usage
The project itself is packed with all source files. In order to add the new flavor to an existing keml.editor, run Generate -> Editor code or Generate -> All on the keml ecore file as described on the [keml model project](https://gitlab.uni-koblenz.de/keml/keml).
You can then start an Eclipse application from the keml.editor to use the edit code.

## Adding more customization
To add further customization, just go into the generated code and remove the `@Generated`annotation of the method you would like to adapt. Further generations will not touch this method any more.
Don't forget to run Generate->Editor Code (or All!) afterwards to have your changes available on an Eclipse editor spawned from the keml.editor.

## Further Reading
More information about model code, edit code and generation can be found on the Eclipse tutorial on [Domain Models](https://wiki.eclipse.org/Sirius/Tutorials/DomainModelTutorial). Further reading about customization, even going beyond edit code customization into Sirius graphical editors is available on the [Eclipse Sirius Starter Tutorial](https://wiki.eclipse.org/Sirius/Tutorials/StarterTutorial).


## License
The license of this project is that of the [group](https://gitlab.uni-koblenz.de/keml).


