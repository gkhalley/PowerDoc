# Electric System Navigation

An electric power system is relatively easy to navigate when it is drawn with the end use in mind. If the purpose is to show a method of protection for a transformer, each component used in the protection, current transformer, relay, and a breakdown within the relay are shown on a single drawing. If the purpose is to show justification for a capacity rating which characterizes a whole area of electrical components with a temperature-related table of values (for example, ambient adjusted ratings), then each component can be listed along with a diagram showing its location relative to the main facility.

An electric system navigation needs to be separated into components and electrical nodes. If we focus on electrical nodes, it can even be broken further. Ignore the components to used to interrupt or isolate power for a safety or control (breakers) and use a bus-branch analysis. This simplifies the system down to a very efficient mathematical model. Contingency analysis is completed by changing state of lines and components with special requirements for how a line is opened. A more real-world system uses a node-breaker analysis which includes the breakers. The node-breaker model is easier to visualize and understand.

In an ideal work you could create a node-breaker system and then be able to go back and forth between bus-branch and node-breaker. Bus-branch might be thought of as the electrical view and node-breaker might be the operational view.
## Nodes (ENodes)


Syntax:

![ENodes.jpg](ENodes.jpg)

## Node-Breaker

Describe what each option is used for:

![Node-Breaker.jpg](Node-Breaker.jpg)

<seealso>
    <!--Provide links to related how-to guides, overviews, and tutorials.-->
</seealso>