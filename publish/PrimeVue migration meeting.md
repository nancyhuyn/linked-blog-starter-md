Goal:
- Discuss our approach and alignment for component standardisation, mainly for CCA and AP
- I'll share context on where we're currently at and where I think we should go

Agenda
1. Context
	1. PrimeVue3 has reached EOL, need to migrate
		- Approach: gradually phase out components
		- Install PV4 and use, it has some default themes
		- To get it to match out theme, we have to override a lot of classes
		- Don't reccommend
			- Can get messy really quickly, especially if you style for variants
			- And this got mee looking at how we were styling PV previously
				- Not standardised
				- What happened because of that...
				- As a a part of this migration, since we have to style the compoenents I thought it would eb a good opportunity to also standardise them
	2. Component standardisation
		- we have components that look different across AP -> show example
		- hard to customize primevue components
		- not aligned with designers -> example
2. Proposal
	- I suggest we add design tokens so we can use primevue OOTB
	- This will support future designs, standardise components in AP and make migration easier
	- How we plan on migrating - phasing out PV3
	- Benefits and drawbacks of tying the codebases together with the component library (Will show that I have thought about it, DIY is a sub app of AP)

Questions for alignment
1. Should CCA and AP be using the same theme for primevue? i.e. should they be using the same design tokens?
2. What are our short-, medium-, and long term goals with component standardisation
3. Standardisation for other apps.... What does everyone else think?

Prior reading for the meeting
Goal: Alignment on CCA and AP and with Dave Hay's thoughts. 


It might actually be better to do the mirgation first....
- If we do them together, the css from the old primevue theme is conflicting with the design tokens
- Hard to resolve
- Can do later