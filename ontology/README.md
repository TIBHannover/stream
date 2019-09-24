# Visualizing the EMMO ontolgoy using VoCol
1. Open Protege (install version 5.5.0 or upper from [here](https://protege.stanford.edu/))
2. Go to **File -> Open** From URL and open the follwoing three ontology modules from the EMMO ontology repository
   * [The core module](https://raw.githubusercontent.com/emmo-repo/EMMO/v0.9.9r2/emmo/core/emmo-core.owl)
   * [The direct module](https://github.com/emmo-repo/EMMO/blob/v0.9.9r2/emmo/core/emmo-direct.owl)
   * [The material module](https://raw.githubusercontent.com/emmo-repo/EMMO/v0.9.9r2/emmo/material/emmo-material.owl)
3. Select emmo-material as the active ontology.
4. Check in Class hierarchy pane that classes such as **electron**, **field**, and **photon** are listed.
5. Select **File -> Save As** and choose **Turtle Syntax** from the list of available formats, then click **OK**.
6. Choose a folder and a file name so that the loaded OWL ontology modules are converted to a single TTL file and saved. For example, `d:\projects\stream\ontology\stream.ttl`. *Do not forget to mention the .ttl extension.*
7. Visit the the [VoCol instance]() in your browser. (if you do not have a VoCol instance, use this [WebVOWL](http://www.visualdataweb.de/webvowl/))
8. In the bottom menubar choose **Ontology**. Then click the **Select ontolgoy file** box and choose the TTL file created in the previous steps. Click **Upload** to upload the file to the server.
   * You may receive a warning message. It is because the material module doe snot use the direct module but has imported it. You can safely neglect the message.
9. The ontolgoy must be displayed in the visualization pane. If not, switch to the visualization pane available on top of the window. You can also visit the documentation pane as well as the property pane that shows the properties of the selected item.
 