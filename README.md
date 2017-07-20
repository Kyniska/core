Core: A Version of Democracy
====

Core aims to translate the organizing principles (laws) from the Constitution of the Haudenosaunee to operational form using Blockchain technology.

# Sources (incomplete)

http://www.onondaganation.org/government/

https://www.amazon.com/Forgotten-Founders-American-Indian-Democracy/dp/0916782905

http://www.nytimes.com/1987/06/28/us/iroquois-constitution-a-forerunner-to-colonists-democratic-principles.html

# Some defining differences:

- Democracy is materiarchal
- Eldest women select candidates for leadership and have ability to remove
- Good leaders hold position for life
- No leader or law accepted without unanimous consent of the people (mostly true)

# Validity

Some may question the authenticity and validity of the sources and claims relating to this effort.  

While we have come to our own conclusions, for our own reasons, we invite all to consider not the validity of the sources or claims, but the principles proposed and their organization.  How likely is this proposal to work, to support and nourish any group of people seeking organizing principles for governance that satisfy and unify? 

# Why only psuedo-code (for now)?

Wishing to honor the purity of the original blockchain network (supporting Bitcoin) the hope was to use the Ethereum network.  However, the Solidity programming language does not afford types of privacy vital to this democratic structure – especially relating to accountability:

“Everything that is inside a contract is visible to all external observers. Making something private only prevents other contracts from accessing and modifying the information, but it will still be visible to the whole world outside of the blockchain.”

https://solidity.readthedocs.io/en/develop/contracts.html#visibility-and-getters

For preserving, or returning to, equilibrium among members, certain types of accountability require feedback between individuals involved to remain private.  
Thus, for the moment, as alternatives like Hyperledger’s Fabric project continue to evolve, the aim is to define the framework and instructions for any language, until a natural fit becomes clear.

# Translating to code

/* 

Reading so far suggests bloodlines/skin color/native language did not take precedence for acceptance (reference needed).  Any individual agreeing to follow the agreed-to laws was accepted into the community.  One challenge, this policy was applied in a context were face-to-face interaction was available - and thus able to authenticate and provide accountability.  Online, false identities are not only possible but widely used.  If accountability plays a vital role in this governmental structure, how to verify the authenticity of any address for inclusion? 

Privacy needs: addresses assigned to roles have permissions to view strings; relating to loyalities and the potential for factions to emerge, if members are assigned to more than one group (as a preventative mechanism, members can only see members of their group?)

Data-types in use:

Addresses: representing presence and identity of individuals and perhaps groups

Strings: representing dominant loyalties of individuals (bloodline, country-of-origin, native language, etc), feedback for accountability (leader is guilty of...)

Bools: receipt of feedback, presence of witness during sharing of feedback

Arrays: holding members of groups and characteristics referencing dominant loyalities

*/


