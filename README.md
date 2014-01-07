NEO4J on AWS EC2
----------------

These CloudFormation templates help the user bootstrap Neo4j onto an Amazon EC2 machine.  They aren't intended for production use.

Caveats:
* They don't use an Oracle JVM
* There's no backup (but they do write to an EBS volume)
* This is unsupported
* Especially when it's not in neo4-contrib

TODO:
* Deploy 2.0 RPM's to yum.neo4j.org
* Make ubuntu and amazon outputs consistent with each other
* Port documentation from the puppet thing
* Make the EBS volume and filesystem for the Amazon Linux template
