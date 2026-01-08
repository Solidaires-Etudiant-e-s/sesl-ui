<template>
  <div>
    <UPageHero
      title="sesl-ui"
      description="🎨 A Nuxt UI layer with curated tokens, polished defaults, and ready-to-ship page patterns. Build quickly without sacrificing taste."
      :links="[{
        label: 'Get started',
        to: 'https://ui.nuxt.com/docs/getting-started/installation/nuxt',
        target: '_blank',
        trailingIcon: 'mingcute:arrow-right-line',
        size: 'xl'
      }, {
        label: 'View source',
        to: 'https://github.com/Solidaires-Etudiant-e-s/ui',
        target: '_blank',
        icon: 'mingcute:github-line',
        size: 'xl',
        color: 'neutral',
        variant: 'subtle'
      }]"
    />

    <UPageSection
      id="features"
      title="Everything you need to build modern Nuxt apps"
      description="Start with a solid foundation. eban-ui bundles Nuxt UI with opinionated tokens, typography, and layouts so you can focus on your product."
      :features="[{
        icon: 'mingcute:rocket-line',
        title: 'Production-ready from day one',
        description: 'Pre-configured with TypeScript, ESLint, Tailwind CSS, and sane defaults. Focus on building features, not setting up tooling.'
      }, {
        icon: 'mingcute:palette-line',
        title: 'Beautiful by default',
        description: 'Curated design tokens, spacing, and typography layered on Nuxt UI so your app looks cohesive out of the box.'
      }, {
        icon: 'mingcute:flash-line',
        title: 'Lightning fast',
        description: 'Optimized for performance with SSR/SSG support, automatic code splitting, and edge-ready deployment. Your users will love the speed.'
      }, {
        icon: 'mingcute:box-line',
        title: '100+ components included',
        description: 'Access Nuxt UI\'s comprehensive component library. From forms to navigation, everything is accessible, responsive, and customizable.'
      }, {
        icon: 'mingcute:code-line',
        title: 'Developer experience first',
        description: 'Auto-imports, hot module replacement, and TypeScript support. Write less boilerplate and ship more features.'
      }, {
        icon: 'mingcute:shield-line',
        title: 'Built for scale',
        description: 'Enterprise-ready architecture with proper error handling, SEO optimization, and security best practices built-in.'
      }]"
    />

    <UPageSection>
      <UPageCTA
        title="Ready to build your next Nuxt app?"
        description="Build with Nuxt UI and eban-ui's ready-made defaults. Clone, tweak, and ship your product today."
        variant="subtle"
        :links="[{
          label: 'Start building',
          to: 'https://ui.nuxt.com/docs/getting-started/installation/nuxt',
          target: '_blank',
          trailingIcon: 'mingcute:arrow-right-line',
          color: 'neutral',
        }, {
          label: 'View on GitHub',
          to: 'https://github.com/Solidaires-Etudiant-e-s/ui',
          target: '_blank',
          icon: 'mingcute:github-line',
          color: 'neutral',
          variant: 'outline'
        }]"
      />
    </UPageSection>
  </div>
</template>
