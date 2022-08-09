# NAME

Perl::Critic::Policy::Modules::RequireExplicitPackage::ObjectPad - Always make the package/Object::Pad class explicit.

# METHOLDS

## violates

Please see [Perl::Critic::Policy::Modules::RequireExplicitPackage::violates](https://metacpan.org/pod/Perl%3A%3ACritic%3A%3APolicy%3A%3AModules%3A%3ARequireExplicitPackage%3A%3Aviolates)

## \_replace\_class

replace 'use Object::Pad' and 'class XXXX' with \`package XXX\` in [PPI::Document](https://metacpan.org/pod/PPI%3A%3ADocument) object, to make it be processable by [Perl::Critic::Policy::Modules::RequireExplicitPackage::violates](https://metacpan.org/pod/Perl%3A%3ACritic%3A%3APolicy%3A%3AModules%3A%3ARequireExplicitPackage%3A%3Aviolates)

Argument: PPI::Document object
Return: cloned PPI::document object
