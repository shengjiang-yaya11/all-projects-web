---
layout: home
title: Noland Electronics - Electronics Sourcing Partner in China
description: Professional electronics sourcing services in Shenzhen. PCB assembly, component procurement, OEM/ODM manufacturing with quality assurance and competitive pricing.
head:
  - ['meta', { name: 'keywords', content: 'electronics sourcing, PCB assembly, electronic components, China manufacturing, OEM ODM, Shenzhen electronics' }]
---

<script setup>
import { ref, onMounted } from 'vue'

const stats = [
  { number: '500+', label: 'Global Clients', icon: '🌍' },
  { number: '10,000+', label: 'SKUs Available', icon: '📦' },
  { number: '50%', label: 'Cost Savings', icon: '💰' },
  { number: '30 Days', label: 'Fast Delivery', icon: '🚚' }
]

const services = [
  {
    icon: '🔧',
    title: 'Electronics Customization',
    desc: 'From concept to production - PCB design, firmware development, prototyping, and full product manufacturing.',
    features: ['PCB Assembly', 'Product Development', 'Firmware', 'Enclosures']
  },
  {
    icon: '📦',
    title: 'Component Sourcing',
    desc: 'Access 10,000+ electronic components from verified suppliers with competitive pricing.',
    features: ['Semiconductors', 'Passive Components', 'Connectors', 'Displays']
  },
  {
    icon: '🎨',
    title: 'POD Service',
    desc: 'Small batch production from 50 units. Perfect for startups and market testing.',
    features: ['Custom Branding', 'Low MOQ', 'Private Label', 'Fast Turnaround']
  },
  {
    icon: '🏢',
    title: 'OEM/ODM Solutions',
    desc: 'Full-service manufacturing partnership with end-to-end supply chain integration.',
    features: ['Build to Spec', 'Design + Build', 'White Label', 'Logistics']
  },
  {
    icon: '✅',
    title: 'Quality Assurance',
    desc: 'International certifications and 100% inspection guarantee.',
    features: ['CE/FCC/RoHS', 'Lab Testing', 'Factory Audits', '1-Year Warranty']
  },
  {
    icon: '🚚',
    title: 'Global Logistics',
    desc: 'Door-to-door shipping worldwide with customs clearance support.',
    features: ['Express Shipping', 'Sea Freight', 'FBA Prep', 'Documentation']
  }
]

const features = [
  { icon: '🏭', title: 'Shenzhen Advantage', desc: 'World\'s electronics capital - complete supply chain access' },
  { icon: '💰', title: 'Competitive Pricing', desc: '40-60% cost reduction vs Western suppliers' },
  { icon: '🔒', title: 'Quality Guaranteed', desc: 'ISO 9001 certified, <0.5% defect rate' },
  { icon: '⚡', title: 'Fast Turnaround', desc: 'Quote in 24h, samples in 7 days' },
  { icon: '🗣️', title: 'No Language Barrier', desc: 'English-speaking team, responsive communication' },
  { icon: '🎨', title: 'Flexible MOQ', desc: 'From 50 units, ideal for startups' }
]

const products = [
  { icon: '📱', name: 'Consumer Electronics', items: 'Smartphones, tablets, wearables' },
  { icon: '🔌', name: 'Electronic Components', items: 'ICs, sensors, modules, dev boards' },
  { icon: '🏠', name: 'Smart Home Devices', items: 'Plugs, cameras, lighting systems' },
  { icon: '🎮', name: 'Gaming Accessories', items: 'Controllers, headsets, chargers' },
  { icon: '🔋', name: 'Power & Charging', items: 'Power banks, adapters, batteries' },
  { icon: '🖨️', name: 'POD Products', items: 'Custom branded electronics' }
]

const processSteps = [
  { num: '1', title: 'Inquiry', desc: 'Send requirements' },
  { num: '2', title: 'Quote', desc: '24h response' },
  { num: '3', title: 'Sample', desc: 'Test before commit' },
  { num: '4', title: 'Production', desc: 'Quality controlled' },
  { num: '5', title: 'Delivery', desc: 'Global shipping' }
]
</script>

<div class="hero-wrap">
  <div class="hero-glow"></div>
  <h1 class="hero-title">
    <span class="gradient-text">Your Trusted Partner</span>
    <span class="sub-text">for Electronics Sourcing in China</span>
  </h1>
  <p class="hero-desc">
    Connecting Global Buyers with China's Electronics Manufacturing Excellence
  </p>
  <a href="/contact" class="hero-btn">
    <span>Get Free Quote</span>
    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
      <path d="M5 12h14M12 5l7 7-7 7"/>
    </svg>
  </a>
</div>

<div class="stats-bar">
  <div v-for="stat in stats" :key="stat.label" class="stat-item">
    <span class="stat-icon">{{ stat.icon }}</span>
    <span class="stat-num">{{ stat.number }}</span>
    <span class="stat-lbl">{{ stat.label }}</span>
  </div>
</div>

<section class="section">
  <h2 class="section-title">🏭 What We Do</h2>
  <p class="section-desc">
    Noland Electronics is a Shenzhen-based sourcing company specializing in electronics customization and component procurement. 
    We help global buyers access China's manufacturing capabilities with quality assurance and competitive pricing.
  </p>
</section>

<section class="section">
  <h2 class="section-title">💼 Our Services</h2>
  <div class="service-grid">
    <div v-for="svc in services" :key="svc.title" class="service-card">
      <span class="svc-icon">{{ svc.icon }}</span>
      <h3>{{ svc.title }}</h3>
      <p>{{ svc.desc }}</p>
      <div class="svc-tags">
        <span v-for="f in svc.features" :key="f" class="svc-tag">{{ f }}</span>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <h2 class="section-title">🎯 Why Choose Us</h2>
  <div class="feature-grid">
    <div v-for="f in features" :key="f.title" class="feature-card">
      <span class="feat-icon">{{ f.icon }}</span>
      <h4>{{ f.title }}</h4>
      <p>{{ f.desc }}</p>
    </div>
  </div>
</section>

<section class="section">
  <h2 class="section-title">📦 Product Categories</h2>
  <div class="product-grid">
    <div v-for="p in products" :key="p.name" class="product-card">
      <span class="prod-icon">{{ p.icon }}</span>
      <h4>{{ p.name }}</h4>
      <p>{{ p.items }}</p>
    </div>
  </div>
</section>

<section class="section">
  <h2 class="section-title">🚀 How to Work with Us</h2>
  <div class="process-bar">
    <div v-for="step in processSteps" :key="step.num" class="process-step">
      <span class="step-num">{{ step.num }}</span>
      <h4>{{ step.title }}</h4>
      <p>{{ step.desc }}</p>
    </div>
  </div>
</section>

<section class="section cta-section">
  <h2 class="section-title">💬 Get Started Today</h2>
  <p class="cta-text">Ready to source electronics from China? Contact us for a free consultation.</p>
  <div class="contact-info">
    <div class="contact-item">
      <span>📧</span>
      <a href="mailto:sandy-chinaet@163.com">sandy-chinaet@163.com</a>
    </div>
    <div class="contact-item">
      <span>📱</span>
      <span>+86 166-2083-9483</span>
    </div>
    <div class="contact-item">
      <span>💬</span>
      <span>WhatsApp / WeChat</span>
    </div>
  </div>
  <a href="/contact" class="cta-btn">Request a Quote →</a>
</section>

<style>
/* Hero Section */
.hero-wrap {
  position: relative;
  text-align: center;
  padding: 4rem 2rem;
  overflow: hidden;
}

.hero-glow {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 600px;
  height: 400px;
  background: radial-gradient(ellipse at center, rgba(37, 99, 235, 0.15) 0%, transparent 70%);
  pointer-events: none;
}

.hero-title {
  font-size: clamp(2.5rem, 6vw, 4rem);
  font-weight: 900;
  line-height: 1.1;
  margin-bottom: 1rem;
  position: relative;
}

.gradient-text {
  background: linear-gradient(135deg, #60a5fa 0%, #2563eb 50%, #06b6d4 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  display: block;
}

.sub-text {
  display: block;
  color: #60a5fa;
  font-size: 0.5em;
  margin-top: 0.5rem;
}

.hero-desc {
  color: #94a3b8;
  font-size: 1.2rem;
  max-width: 600px;
  margin: 0 auto 2rem;
}

.hero-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: linear-gradient(135deg, #2563eb, #06b6d4);
  color: white;
  padding: 1rem 2.5rem;
  border-radius: 50px;
  font-weight: 700;
  font-size: 1.1rem;
  text-decoration: none;
  transition: all 0.3s ease;
  box-shadow: 0 4px 20px rgba(37, 99, 235, 0.3);
}

.hero-btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 30px rgba(37, 99, 235, 0.4);
}

/* Stats Bar */
.stats-bar {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 1rem;
  max-width: 900px;
  margin: 0 auto 3rem;
  padding: 0 1rem;
}

.stat-item {
  background: rgba(37, 99, 235, 0.08);
  border: 1px solid rgba(37, 99, 235, 0.2);
  border-radius: 12px;
  padding: 1.2rem;
  text-align: center;
  transition: all 0.3s ease;
}

.stat-item:hover {
  border-color: rgba(37, 99, 235, 0.5);
  transform: translateY(-2px);
}

.stat-icon {
  font-size: 1.5rem;
  display: block;
  margin-bottom: 0.3rem;
}

.stat-num {
  font-size: 1.8rem;
  font-weight: 900;
  background: linear-gradient(135deg, #60a5fa, #2563eb);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.stat-lbl {
  font-size: 0.8rem;
  color: #64748b;
}

/* Sections */
.section {
  max-width: 1100px;
  margin: 0 auto 3rem;
  padding: 0 1.5rem;
}

.section-title {
  font-size: 1.8rem;
  font-weight: 800;
  text-align: center;
  margin-bottom: 1.5rem;
  background: linear-gradient(135deg, #60a5fa, #2563eb);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.section-desc {
  text-align: center;
  color: #94a3b8;
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.8;
}

/* Service Grid */
.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 1.5rem;
}

.service-card {
  background: rgba(30, 58, 95, 0.2);
  border: 1px solid rgba(37, 99, 235, 0.15);
  border-radius: 16px;
  padding: 1.5rem;
  transition: all 0.3s ease;
}

.service-card:hover {
  border-color: rgba(37, 99, 235, 0.4);
  transform: translateY(-4px);
  box-shadow: 0 12px 40px rgba(37, 99, 235, 0.1);
}

.svc-icon {
  font-size: 2rem;
  display: block;
  margin-bottom: 0.8rem;
}

.service-card h3 {
  color: #60a5fa;
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
}

.service-card p {
  color: #94a3b8;
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.svc-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.svc-tag {
  background: rgba(37, 99, 235, 0.15);
  color: #60a5fa;
  padding: 0.25rem 0.75rem;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 500;
}

/* Feature Grid */
.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.2rem;
}

.feature-card {
  background: rgba(30, 58, 95, 0.15);
  border: 1px solid rgba(37, 99, 235, 0.1);
  border-radius: 12px;
  padding: 1.2rem;
  transition: all 0.3s ease;
}

.feature-card:hover {
  border-color: rgba(37, 99, 235, 0.3);
}

.feat-icon {
  font-size: 1.5rem;
  display: block;
  margin-bottom: 0.5rem;
}

.feature-card h4 {
  color: #60a5fa;
  font-size: 1rem;
  margin-bottom: 0.3rem;
}

.feature-card p {
  color: #94a3b8;
  font-size: 0.85rem;
}

/* Product Grid */
.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
}

.product-card {
  background: linear-gradient(135deg, rgba(30, 58, 95, 0.3), rgba(15, 23, 42, 0.5));
  border: 1px solid rgba(0, 212, 255, 0.15);
  border-radius: 12px;
  padding: 1.2rem;
  text-align: center;
  transition: all 0.3s ease;
}

.product-card:hover {
  border-color: rgba(0, 212, 255, 0.4);
  transform: translateY(-3px);
}

.prod-icon {
  font-size: 2rem;
  display: block;
  margin-bottom: 0.5rem;
}

.product-card h4 {
  color: #60a5fa;
  font-size: 1rem;
  margin-bottom: 0.3rem;
}

.product-card p {
  color: #94a3b8;
  font-size: 0.85rem;
}

/* Process Bar */
.process-bar {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}

.process-step {
  flex: 1;
  min-width: 140px;
  max-width: 180px;
  text-align: center;
  position: relative;
}

.step-num {
  width: 48px;
  height: 48px;
  background: linear-gradient(135deg, #2563eb, #06b6d4);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 900;
  font-size: 1.2rem;
  color: white;
  margin: 0 auto 0.8rem;
  box-shadow: 0 4px 15px rgba(37, 99, 235, 0.3);
}

.process-step h4 {
  color: #60a5fa;
  font-size: 1rem;
  margin-bottom: 0.3rem;
}

.process-step p {
  color: #94a3b8;
  font-size: 0.85rem;
}

/* CTA Section */
.cta-section {
  text-align: center;
  background: linear-gradient(135deg, rgba(37, 99, 235, 0.1), rgba(6, 182, 212, 0.05));
  border-radius: 24px;
  padding: 3rem 2rem !important;
  margin-top: 2rem;
}

.cta-text {
  color: #94a3b8;
  margin-bottom: 1.5rem;
}

.contact-info {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin-bottom: 2rem;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  color: #60a5fa;
}

.contact-item a {
  color: #60a5fa;
  text-decoration: none;
}

.contact-item a:hover {
  text-decoration: underline;
}

.cta-btn {
  display: inline-block;
  background: linear-gradient(135deg, #2563eb, #06b6d4);
  color: white;
  padding: 1rem 2.5rem;
  border-radius: 50px;
  font-weight: 700;
  font-size: 1.1rem;
  text-decoration: none;
  transition: all 0.3s ease;
  box-shadow: 0 4px 20px rgba(37, 99, 235, 0.3);
}

.cta-btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 30px rgba(37, 99, 235, 0.4);
}

/* Responsive */
@media (max-width: 768px) {
  .stats-bar {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .service-grid {
    grid-template-columns: 1fr;
  }
  
  .feature-grid {
    grid-template-columns: 1fr;
  }
  
  .product-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .process-bar {
    flex-direction: column;
    align-items: center;
  }
  
  .process-step {
    max-width: 100%;
  }
}
</style>
