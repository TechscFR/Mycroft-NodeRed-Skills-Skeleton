# Mycroft-NodeRed-Skills-Skeleton
Mycroft NodeRed Start Skeleton 

Not available now !!!!!

This groups of nodes is a starter to use and create mycroft skills with NodeRed based of the works of @JarbasSkills from his mycroft-node-red repository so you must have it do have the following working.

You will see @JarbasSkills implents 2 node type one fallback and one converse. I dont use it because, i think most on cases gonna have a specifique converse flow, instead i use the following tricks : speak a punctuation that is not write by mycroft when you speak to it (at this point i use comma). Detect that punctuation with a function. I use comma because after a comma, we nedd a little time to think about the residue of the sentence. I have 3 cases in mynd.\n
First with the keyword and the subflow "mode écriture" (translate: writting mode) you need time to think after and you dont wanna say your wake word at the middle of an sentence or after each sentence.
Second, you would activate an API to do, for example, CRUD operations, like you can see with the subflows wich containt the word dolibarr. If would writte some text, you certainly use a note app. If you want to add a product on the dolibbar ERP, for example, you certainly want add a description. In this two case you can use the "mode écriture".
The last case is a real converse. For now i dont use subflow because each converse is different than an other.

To grab the node Copy what is in the folder and copy it in the import tools of NodeRed
