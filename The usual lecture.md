# The usual lecture from the local System Administrator
Systems administration is a complex web of everyday ethical situations.  Consider that the sysadmin runs into a problem where he/she encounters a file with salary information is not loading correctly due to a request from finance, the sysadmin knows its against company policy for him/her to know salary data but finance needs immediate assistance before they make changes to payroll.  Or consider that a company has decided to restructure, the sysadmin will need to work with HR to come up with a plan to safely disable accounts across the organization, coworkers who see it coming might try to make small talk of it, should the sysadmin lie?  Sysadmins whether we like it or not have for a long time now been a very critical underpinning of organizations in that we know things others can’t, see things others can’t and often become aware of private details by accident.  It is truly astonishing the windows people forget to close before asking you to take a seat.  The guidance below is given in Debian systems upon your first time using the sudo command.

```bash
We trust you have received the usual lecture from the local System
Administrator. It usually boils down to these three things:

   #1) Respect the privacy of others.
   #2) Think before you type.
   #3) With great power comes great responsibility.

root's password:
```

If you haven’t had your local Systems Administrator give you that talking to consider this blog post you’re talking to session.

Computers, networks and the internet at large are young things, as such we have not had enough time, failure, success or philosophical minds to mull over a code ethics of systems administrators, developers or network engineers.  We don’t have some ridged well thought out code to ponder and although some organizations such as LOPSA do [_cover the basics_](https://lopsa.org/CodeOfEthics) for the systems administrator our field moves so rapidly that the term systems administrator may not exist in 5-7 years as it becomes quickly out of fashion with the rise of hip titles like “site reliability engineer” or “DevOps dude/dudette”.  Some titles of the future will have much further reaching consequences that deal with questions like “is it ethical to build a system that houses such data that it can be administered?” or “If we train machine learning to account for human bias do we give it access hold encrypted keys no human is allowed to touch to make decisions that seem unethical to decide on for humans?”. 

The Society of Professional Journalists has an [_excellent code of ethics_](https://www.spj.org/ethicscode.asp) It’s an excellent read and has clearly been thought through by philosophic types many times over.  It more or less boils down to the following principles:

1. Seek Truth and Report It.
2. Ethical journalism treats sources, subjects, colleagues, and members of the public as human beings deserving of respect.
3. The highest and primary obligation of ethical journalism is to serve the public.
4. Ethical journalism means taking responsibility for one’s work and explaining one’s decisions to the public.
