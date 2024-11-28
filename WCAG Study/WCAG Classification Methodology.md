We categorized the WCAG success criteria using the following approach. First, we defined the characteristics of issues that require static analysis and those that require dynamic analysis. Static analysis involves examining HTML, CSS, and JavaScript code without executing it, while dynamic analysis requires interactions with the application to gather useful information. Then, we reviewed all the success criteria in the WCAG and attempted to map each one to either static or dynamic analysis. For example, the screenshot below demonstrates the success criterion SC 2.4.6 falls under static analysis since the goal of it is that a page’s content is described in headings and labels. According to the definition, it can be achieved by examining HTML.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfcbbOQn8BOpadQCZTkM3McySVhA_nQWi9TphyTA9l1JxaqDxTzbU9ocp1qy_yNWufBS5RpBqD5nOzKbMFwjJEvITG4G6mcnrmh_5Vm0nZ-5Ru89VFz7SyEC8ylMVjjrqyN2QGpcw?key=mx2ET2eS5ycclHd4oSNJdiI6)



By contrast, the screenshot of SC 2.5.1 below indicates it needs analysis, as illustrated by the keyword “Let users operate” in its Goal.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdbPybhfUMbJQbYvucvpiv_dZ_fHIQtS8oYQxrcSiU0xrbVDzG4d_v4INH_y6ICjEH7a0N85b8eVuHQCuQ4VttkkKd6vssfugJv8P4Q5UgZoCWBswTDI00u4PAdS6s9pshteT-DHw?key=mx2ET2eS5ycclHd4oSNJdiI6)



During this process, we found that certain success criteria are not testable, as specifically noted by the WCAG—for example, success criterion 3.1.5 Reading Level. This led us to establish a third category for untestable criteria. 

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd8vT6bGpeadpL-YLZfSwkRl0qu-Ty_eKeR6-w5E51LIfr2lAumSwxVxMGQmhYc2JFErzYhy272FZBsRMri_lR5GFGAHDq1N_35scA5hq45JhWRd_W9LJvolW6cOoxYvPGyC6j7?key=mx2ET2eS5ycclHd4oSNJdiI6)



To ensure the reliability of our classification of WCAG success criteria into static and dynamic analysis categories, we performed cross-validation using the documentation of two widely used accessibility evaluation tools: WAVE and IBM Equal Access. We observed that success criteria documented with specific violations in these tools typically fall under **static analysis**, as these violations can be detected from the code without requiring user interaction. Conversely, success criteria that are mentioned without specified violations often require **dynamic analysis**, involving user interactions or behaviors that cannot be assessed through static code inspection alone.

For example, in the IBM Equal Access documentation, **SC 3.1.1 Language of Page** has several documented violations—such as missing lang attributes—that can be identified through static analysis.![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcZxZfHAK7yvTzt39fbh51V631uBluqlkRdYy5RZyQs_et1avMDaozqrM3BJ2Cq7g0BC-2tepUjs6wATsCpz8WtpJR0NU0HBKXi55bF9tA_q24IWky64-8WrZhgqCtE6RHWMSKklw?key=mx2ET2eS5ycclHd4oSNJdiI6)



In contrast, **SC 2.5.1 Pointer Gestures** and **SC 2.5.2 Pointer Cancellation** lack specific documented violations and involve user interactions like multi-point gestures or touch events, indicating the need for dynamic analysis. By cross-referencing the presence or absence of documented violations and considering the nature of each success criterion, we validated our classification into static and dynamic categories.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcpF2f5ax5KzZJ8gDcSUPY-5YP7Mk-rAGxL-spcmvFDaDvGFlvzHSsjyLya0msDfGTLIOdPMcTP_UeAbQknRBIFAJbadT6tAHrLwr2kddZ09BhVwffiJmkyGDm2anxZp2Lkf5DHZg?key=mx2ET2eS5ycclHd4oSNJdiI6)