![Photo](images/photo.jpg)
# **Yauheni Karasiuk**
Lead Software Engineer at EPAM
# **Contact Information**
* **Location:** Minsk, Belarus
* **Phone:** +375333798409
* **Email:** yauheni.karasiuk@gmail.com
* **Telegram:** t.me/yauheni_k49
# **About Myself**
I'm ServiceNow Developer with 6 years of experience implementing complex solutions for wide varyity of clients from USA, Europe and UAE.

I can say that I'm passioned about learning, doing my best to be aware of cutting edge technologies related to my working field.

Mostly main reason to attend rs.school is that React framework is now driving ServiceNow Front-End Development and rs.school classes, I think, is the best way to gain Front-End and especially React skills.
# **Skills**
* ServiceNow Development
* ITIL
* REST/SOAP Integrations
* Agile/Scrum/Kanban Methodologies
* Team Leading
* Prototyping and estimations
# **Code Examples**
(In ServiceNow we use ES5, so please don't be mad about use of 'var' :rofl:)
```
var gr = new GlideRecord('incident');
gr.addQuery('state', 1);
gr.addQuery('assignment_group.active', false);
gr.query();
while(gr.next()){
    gr.setValue('active', false);
    gr.comments = 'Inactivating incident because it's assigned to inactive group';
    gr.update();
}
```