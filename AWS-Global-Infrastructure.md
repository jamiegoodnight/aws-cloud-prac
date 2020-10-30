<h1>AWS Global Infrastructure</h1>

<p>AWS Serves over a million active customers. 

Regions - Physical location in the world with multiple availability zones. 

Availability Zones - One or more discrete data centers.

Edge Locations - Data center owned by trusted AWS partner.</p>

<h2>Regions</h2>

<p>Every region is isolated from and independent from every other region in terms
of location/power/water.

Each region has at least two AZs.

AWS's largest region is US-EAST. Not all services available in all region. 

US-EAST-1 is where you see billing info.</p>

<h2>Availability Zones</h2>

<p>Data center owned and operated by AWS. AZs are represented by Region Code followed by
a letter identifier. Multi-AZ distrubution allows failover config for handling requests when
one goes down. Latency between AZs is less than 10ms.</p>

<h2>Edge Location</h2>

<p>Serve requests for CloudFront and Route 53. Edge Locations allow for low latency 
no matter where the user is located. Serving responses quickly.</p>

<h2>GovCloud Regions</h2>

<p>Allow customers to host sensitive Controlled Unclassified Information. Only
accessible to US entities.</p>