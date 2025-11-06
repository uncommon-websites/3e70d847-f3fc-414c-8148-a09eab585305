<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconAward from "~icons/lucide/award";
	import IconUsers from "~icons/lucide/users";
	import IconHeart from "~icons/lucide/heart";
	import IconBarChart from "~icons/lucide/bar-chart";
	import IconHeadphones from "~icons/lucide/headphones";
	import IconSettings from "~icons/lucide/settings";
</script>

<CenteredTextOnlyHero
	title="Evidence-based suicide prevention training that saves lives"
	subtitle="Empower your organization with proven intervention skills through scalable gatekeeper programs trusted by crisis counselors and mental health professionals."
	imageSrc="/generated/image-a-medium-shot-of-a-diverse-group-of-thre.webp"
/>
<LogoScroller
	label="Trusted by organizations committed to mental health"
	logoUrls={[
		'https://cdn.brandfetch.io/kp.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/ucsf.edu/w/400/h/400/logo',
		'https://cdn.brandfetch.io/deloitte.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/starbucks.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Living Works provides evidence-based suicide prevention training programs designed for organizations that need scalable, effective solutions. We serve suicide prevention coordinators, HR directors, and mental health professionals at mid-size companies who are committed to protecting their communities. Our proven gatekeeper programs equip crisis counselors and staff with life-saving intervention skills, transforming the $8B mental health market one trained individual at a time."
/>

<Testimonials
	testimonials={[
		{
			name: "Mei Chen",
			position: "Director of People Operations",
			company: "TechForward Inc",
			quote:
				"Living Works cut our training rollout time by 60%. We trained 200 employees in three weeks instead of two months. The virtual format meant zero travel costs and the certification tracking saved our HR team 15 hours per week.",
			image: "/generated/image-a-professional-asian-woman-hr-director-s.webp"
		},
		{
			name: "Marcus Williams",
			position: "Mental Health Coordinator",
			company: "Metropolitan Health Network",
			quote:
				"After implementing Living Works, our early intervention rates increased by 40%. Three employees told us the training gave them confidence to reach out when they noticed warning signs. That direct impact is impossible to put a price on.",
			image: "/generated/image-a-professional-black-man-mental-health-c.webp"
		},
		{
			name: "Rosa Gutierrez",
			position: "Workplace Wellness Manager",
			company: "Horizon Financial Group",
			quote:
				"The evidence-based protocols gave our leadership the confidence to invest. We avoided the cost of bringing in external consultants, saving $45,000, and saw a 28% reduction in crisis-related absences within the first six months.",
			image: "/generated/image-a-professional-latina-woman-workplace-we.webp"
		}
	]}
/>

<Features
	title="Why organizations choose Living Works"
	subtitle="Evidence-based training programs designed to scale across your organization while delivering measurable suicide prevention outcomes."
	features={[
		{
			title: "Evidence-based protocols",
			description:
				"Our gatekeeper programs are grounded in peer-reviewed research and clinical best practices. Training methodologies are proven to increase intervention confidence and save lives.",
			icon: IconAward
		},
		{
			title: "Scalable training delivery",
			description:
				"Train thousands of employees efficiently with flexible formats that fit your organization's needs. From crisis counselors to HR teams, our programs scale without sacrificing quality.",
			icon: IconUsers
		},
		{
			title: "Engaging learning experience",
			description:
				"Interactive scenarios and practical skill-building keep participants engaged and retain knowledge long-term. Our completion rates exceed industry standards by 40%.",
			icon: IconHeart
		},
		{
			title: "Measurable impact tracking",
			description:
				"Demonstrate ROI with comprehensive analytics that track training completion, skill competency, and intervention outcomes. Real data that justifies your investment.",
			icon: IconBarChart
		},
		{
			title: "Implementation support",
			description:
				"Our team guides you from pilot to full deployment with dedicated onboarding and ongoing assistance. You're never alone in building your prevention program.",
			icon: IconHeadphones
		},
		{
			title: "Customizable to your context",
			description:
				"Adapt training content to reflect your organization's culture, policies, and specific risk factors. One size doesn't fit all in suicide prevention.",
			icon: IconSettings
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start training today. Save lives tomorrow."
	subtitle="Ready to make it count?"
	description="You don't need to be a mental health expert to make a difference. Living Works gives your team the confidence to act when it matters most. Join organizations reducing liability, improving wellbeing, and protecting what truly matters: people."
	imageSrc="/generated/image-a-professional-woman-hr-director-stands-.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Schedule a demo",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
