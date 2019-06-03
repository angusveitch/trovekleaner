# trovekleaner
A Knime workflow to correct OCR errors in large collections of documents.

As the blurb says, this workflow fixes OCR errors in large collections of text such as the archived newspaper articles available from www.trove.nla.gov.au. Be warned, however, that the workflow is highly experimental and is not designed to fix every error an a collection. Rather, it uses a combination of methods to identify pairs of likely errors and corrections. From these pairs it builds a dictionary that is used to replace all occurrences of the errors. Basically it is an experiment that got way out of hand.

To run this workflow, you will first need to have Knime installed. Then all you need to do is download the knwf file and import it from within Knime using the command 'Import KNIME workflow' under 'File'.

To use the workflow, you will also need to feed it some text data. You can build your own collection of newspaper articles data from Trove using the Trove KnewsGetter workflow, which is also available on my GitHub. Or you can use data from anywhere, as long as the column names are compatible with the workflow. Otherwise, you can use the sample of 3,000 articles contained within BC-1890-4_Sample.zip within this repository.

Further instructions can be found in the form of annotations throughout the workflow. In addition, you should read my detailed blog post about the worfklow at http://seenanotherway.com/trovekleaner.

If you have any questions or find any bugs, please get in touch!
-Angus
