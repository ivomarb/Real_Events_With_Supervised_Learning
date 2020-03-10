# Real Events With Supervised Learning

Monitoring company: any company that uses a platform to handle signals (events) arising from electronic alarm systems (with motion sensors,
for example), cameras, etc.

One of the biggest cost drivers for monitoring companies is displacement, that is, when the company needs to send a vehicle (car or motorcycle) to the residence or business being monitored.

It happens that many times these shots are caused by different scenarios, such as: a tree branch swaying in the wind, storms, animals, or even by the client himself wanting to do a test to see if the monitoring company is really watching.

Based on the train.cvs and test.cvs files, an algorithm was developed to predict whether the shot is false or true, indicating the accuracy of the result.

Data dictionary:

<ul>

<li>Customer code: Unique customer code within the system;</li>
<li>Risk level: Degree of danger of the place, with 5 being the highest;</li>
<li>Has CCTV server: Indicates whether the client has image monitoring (0: no; 1: yes);</li>
<li>Individual, legal entity or public body: 0 = legal person, 1 = physical person, 2 = public body;</li>
<li>State, City, Neighborhood: Locality of the client;</li>
<li>Date/time: Date / time of the event;</li>
<li>Event code: Event code sent;</li>
<li>Confirmed: Indicates if there was a claim on the customer (0: no, 1: yes).</li>

</ul>
