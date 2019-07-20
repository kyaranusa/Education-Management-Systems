# Education-Management-Systems


Education Management System is open source student and staff adminstration software for educational institutions that caters for admissions, clearance, course registration, grading, exams processing and transcripts. It comes with plugins for creating and synchronizing user accounts on e-mail servers, payment administration, HR management and a flexible reporting system.

EMS is based on these great works of

1. OdooEduERP https://github.com/JayVora-SerpentCS/OdooEduERP 
2. OpenEduCat https://github.com/openeducat/openeducat_erp#12.0

Programming Language: Python
OS: Linux, Windows, Machintos, open platform.

Version 1.0.0: 
- Totally a cloning of OdooEduERP with 1 improvement at exam module, just a small bug fixing, but it bothered me, this bug was my main reason to start this project, sharing back the work to community
- File "/odoo/custom/addons/OdooEduERP/exam/models/exam.py", line 106, in onchange_date_day
    week_day = datetime.strptime(rec.exm_date, "%Y-%m-%d"). TypeError: strptime() argument 1 must be str, not datetime.date, FIXED

Links:
- OdooEduERP: https://www.odoo.com/apps/modules/12.0/school/
- Odoo Platform: https://www.odoo.com/
- Odoo Installer : https://www.getopenerp.com/install-odoo-12-on-ubuntu-18-04/
- Odoo Installer with single script : https://github.com/Yenthe666/InstallScript

kikik yaranusa
PT Integra Solusi Utama
