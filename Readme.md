# **flowClean-Plugin**

# **Description**

FlowClean is an algorithm that automatically identifies and flags fluorescence anomalies in flow cytometry data so that these can be easily removed. The FlowClean algorithm utilizes the R statistical computing environment and is implemented in FlowJo as a plugin that integrates flowClean’s functionality into FlowJo version 10.1r7.

# **Dependencies**

This plugin requires R and the packages "flowCore" and “flowClean.” Ensure that you have both of these components installed within R prior to launching the plugin.

# **Installation Instructions**

1. To install these packages, open enter the following into your open R console: 

    1. source("https://bioconductor.org/biocLite.R")

biocLite("flowCore") biocLite(“flowClean”)

2. To install the FlowClean plugin:

    2. Download FlowClean.jar from the FlowJo Exchange.

    3. Place the FlowClean.jar file in your Plugins folder.

    4. Restart FlowJo and FlowClean should appear as an option within the Plugins menu.

# **Disclaimer:**

Any links to third-party products or applications available on this website are provided "as is" without warranty of any kind, either expressed or implied and such products and applications are to be used at your own risk.  The third-party products and applications made available on this website/application are provided by parties unaffiliated with FlowJo, LLC.  The use of links to products and applications on this website is done at your own discretion and risk and with the agreement that you will be solely responsible for any damage to your computer system or loss of data that results from such activities.  FlowJo, LLC makes no warranties, express or implied, regarding the conditions of merchantability or fitness for particular purpose of any third-party product or application offered on this website.  FlowJo, LLC makes no representations about the functionality, accuracy, availability, quality, completeness, validity, or non-infringement of third-party rights to any third-party product or application offered on the website.  You are solely responsible for adequate protection and backup of the data and equipment used in connection with any of the software linked to this website, and we will not be liable for any damages that you may suffer in connection with downloading, installing, using, running, modifying, or distributing such software.  FlowJo, LLC does not warrant or endorse and does not assume, nor will it have, any liability or responsibility to any person or legal entity regarding the functionality, accuracy, availability, quality, completeness, validity, or non-infringement of third-party rights of any third-party product or application offered on the website. No advice or information of any kind, whether oral or written, obtained by you from us of rom this website shall create any warranty for third-party product or application made available on this website.  Specifically, FlowJo, LLC makes no warranty that:

            	-Third-party products or applications will meet your requirements.

            	-Third-party products or applications will be uninterrupted, timely, secure, or error-free.

            	-The results from the use of third-party products or applications will be effective, accurate, or reliable.

            	-If errors or problems occur in connection with any download of third-party products or applications from this website, they will be corrected.

FlowJo, LLC further advises users of third-party products or applications from this website that such products, applications, and any associated documentation made available are subject to the following conditions, which by using, you fully accept:

            	-The products or applications could include technical or other mistakes, inaccuracies, or typographical errors.

            	-Changes to the links pointing to third-party products, applications, or documentation on this website may be changed at any time, without prior notice.

            	-FlowJo, LLC accepts and assumes no responsibility for errors or omissions in the third-party products, applications, or documentation available from this website.

            	-At no point will FlowJo, LLC be liable to you or any third-parties for any special, punitive, incidental, consequential, or indirect damages of any kind, or any damages whatsoever, including, without limitation, those resulting from loss of use, lost data, infringement of any other party’s intellection property rights, lost profits, or any liability arising out of or in connection with the use of this third-party product, application, or documentation.

# **flowClean Plugin Documentation**

[https://flowjo-plugin/content/](https://flowjo-plugin/content/)

**flowClean Plugin References**

1. Fletez-Brant, K. et al. (2016) flowClean: Automated identification and

removal of fluorescence anomalies in flow cytometry data. Cytometry A,

DOI:  10.1002/cyto.a.22837. [Epub ahead of print]

2. Fletez-Brant, K. flowClean Reference Manual, version 1.5.1, 2015.

Available at

https://www.bioconductor.org/packages/devel/bioc/manuals/flowClean/

man/flowClean.pdf.

3. [Link to flowClean package on Bioconductor](https://www.bioconductor.org/packages/flowClean/)

