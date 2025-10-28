<template>
  <section id="servicios" class="py-12 bg-gradient-to-br from-blue-50 via-white to-blue-50 relative overflow-hidden w-full flex justify-center">
    <!-- Background Elements -->
    <div class="absolute inset-0 overflow-hidden">
      <div class="absolute top-0 left-0 w-full h-32 bg-gradient-to-b from-white to-transparent"></div>
      <div class="absolute bottom-0 left-0 w-full h-32 bg-gradient-to-t from-white to-transparent"></div>
      
      <!-- Animated Background Shapes -->
      <div class="absolute -top-20 -left-20 w-64 h-64 bg-blue-500/5 rounded-full animate-float-delayed"></div>
      <div class="absolute -bottom-20 -right-20 w-64 h-64 bg-blue-400/5 rounded-full animate-float"></div>
      <div class="absolute top-1/2 left-1/3 w-16 h-16 bg-blue-500/10 rounded-full animate-pulse-slow"></div>
    </div>
    
    <div class="w-full max-w-7xl mx-auto px-4 relative z-10 flex flex-col items-center">
      <!-- Section Header -->
      <div class="text-center w-full flex flex-col items-center mb-16">
        <div class="inline-flex items-center bg-white/80 backdrop-blur-sm rounded-full px-6 py-3 mb-20 border border-blue-200 shadow-lg">
          <div class="w-2 h-2 bg-gradient-to-r from-blue-600 to-blue-800 rounded-full mr-3 animate-pulse"></div>
          <span class="text-sm font-semibold text-gray-600">💎 NUESTROS PLANES PREMIUM</span>
        </div>

        <!-- ESPACIO EXTRA ANTES DE TECHNOLOGY & PROMISE -->
      <div class="h-5 w-full"></div>
        
        <h2 class="text-5xl md:text-6xl font-black mb-8 bg-gradient-to-r from-gray-800 via-blue-800 to-blue-900 bg-clip-text text-transparent text-center w-full">
          Servicios Exclusivos
        </h2>
        <p class="text-xl text-gray-600 max-w-3xl leading-relaxed text-center mx-auto mb-24">
          Descubre nuestros planes <span class="font-semibold text-blue-600">premium</span> diseñados para catapultar tu presencia digital al siguiente nivel
        </p>
      </div>
      
      <!-- ESPACIO EXTRA ENTRE EL HEADER Y EL GRID -->
      <div class="h-16 w-full"></div>
      
      <!-- Services Grid -->
      <div class="grid grid-cols-1 lg:grid-cols-2 xl:grid-cols-4 gap-8 w-full justify-items-center items-stretch relative">
        
        <!-- Plan Básico -->
        <div class="group relative w-full max-w-sm flex flex-col">
          <div class="absolute inset-0 bg-gradient-to-br from-blue-500/10 to-blue-600/10 rounded-3xl transform group-hover:scale-105 transition-transform duration-500"></div>
          <div class="relative bg-white/80 backdrop-blur-sm rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500 transform group-hover:-translate-y-4 border border-blue-200/50 overflow-hidden w-full flex flex-col flex-1">
            <!-- Header -->
            <div class="p-8 text-center border-b border-blue-200/50 flex-shrink-0 flex flex-col items-center justify-center">
              <div class="w-24 h-24 bg-gradient-to-br from-blue-500 to-blue-700 rounded-2xl flex items-center justify-center mb-16 transform transition-all duration-500 group-hover:scale-110 group-hover:rotate-6 shadow-lg">
                <span class="text-3xl text-white">🌱</span>
              </div>
              <h3 class="text-2xl font-black text-gray-800 mb-4">Startup</h3>
              <p class="text-gray-500 font-semibold">Ideal para Emprendedores</p>
            </div>
            
            <!-- Price -->
            <div class="p-6 bg-gradient-to-r from-blue-50 to-white text-center flex-shrink-0">
              <div class="text-4xl font-black text-gray-800 mb-1">$299.999</div>
              <div class="text-gray-500 text-sm">Pago único • Incluye hosting 1 año</div>
            </div>
            
            <!-- Features -->
            <div class="p-6 flex-grow">
              <ul class="space-y-4">
                <li v-for="(feature, index) in basicFeatures" :key="index" 
                    class="flex items-center transform transition-all duration-300 group-hover:translate-x-2">
                  <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center mr-4 flex-shrink-0 group-hover:bg-blue-200 transition-colors duration-300">
                    <span class="text-blue-500 text-lg">✓</span>
                  </div>
                  <span class="text-gray-600 font-medium text-left">{{ feature }}</span>
                </li>
              </ul>
            </div>
            
            <!-- CTA -->
            <div class="p-6 pt-0 flex-shrink-0">
              <button class="w-full bg-gradient-to-r from-blue-600 to-blue-800 hover:from-blue-700 hover:to-blue-900 text-white font-bold py-4 px-6 rounded-xl transition-all duration-500 transform hover:scale-105 shadow-lg hover:shadow-xl relative overflow-hidden group">
                <span class="relative z-10">Comenzar Proyecto</span>
                <div class="absolute inset-0 bg-white/20 transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left"></div>
              </button>
            </div>
          </div>
        </div>

        <!-- Plan Estándar - MÁS POPULAR -->
        <div class="group relative w-full max-w-sm flex flex-col">
          <!-- Cartel MÁS POPULAR JUSTO ARRIBA DE ESTA TARJETA -->
          <div class="absolute -top-8 left-1/2 transform -translate-x-1/2 z-20 w-full max-w-[200px]">
            <span class="bg-gradient-to-r from-blue-600 to-blue-800 text-white text-sm font-black py-3 px-6 rounded-full shadow-2xl w-full block text-center">
              ⭐ MÁS POPULAR
            </span>
          </div>
          <div class="absolute inset-0 bg-gradient-to-br from-blue-600/10 to-blue-700/10 rounded-3xl transform group-hover:scale-105 transition-transform duration-500"></div>
          <div class="relative bg-white/80 backdrop-blur-sm rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500 transform group-hover:-translate-y-4 border-2 border-blue-500/50 overflow-hidden w-full flex flex-col flex-1">
            <!-- Header -->
            <div class="p-8 text-center border-b border-blue-200/50 flex-shrink-0 flex flex-col items-center justify-center">
              <div class="w-24 h-24 bg-gradient-to-br from-blue-600 to-blue-800 rounded-2xl flex items-center justify-center mb-16 transform transition-all duration-500 group-hover:scale-110 group-hover:rotate-6 shadow-lg">
                <span class="text-3xl text-white">🚀</span>
              </div>
              <h3 class="text-2xl font-black text-gray-800 mb-4">Growth</h3>
              <p class="text-gray-500 font-semibold">Pequeñas Empresas</p>
            </div>
            
            <!-- Price -->
            <div class="p-6 bg-gradient-to-r from-blue-50 to-blue-100 text-center flex-shrink-0">
              <div class="text-4xl font-black text-gray-800 mb-1">$599.999</div>
              <div class="text-gray-500 text-sm">Pago único • SEO Avanzado Incluido</div>
            </div>
            
            <!-- Features -->
            <div class="p-6 flex-grow">
              <ul class="space-y-4">
                <li v-for="(feature, index) in standardFeatures" :key="index" 
                    class="flex items-center transform transition-all duration-300 group-hover:translate-x-2">
                  <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center mr-4 flex-shrink-0 group-hover:bg-blue-200 transition-colors duration-300">
                    <span class="text-blue-500 text-lg">✓</span>
                  </div>
                  <span class="text-gray-600 font-medium text-left">{{ feature }}</span>
                </li>
              </ul>
            </div>
            
            <!-- CTA -->
            <div class="p-6 pt-0 flex-shrink-0">
              <button class="w-full bg-gradient-to-r from-blue-600 to-blue-800 hover:from-blue-700 hover:to-blue-900 text-white font-bold py-4 px-6 rounded-xl transition-all duration-500 transform hover:scale-105 shadow-lg hover:shadow-xl relative overflow-hidden group">
                <span class="relative z-10">Elegir Plan</span>
                <div class="absolute inset-0 bg-white/20 transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left"></div>
              </button>
            </div>
          </div>
        </div>

        <!-- Plan Profesional -->
        <div class="group relative w-full max-w-sm flex flex-col">
          <div class="absolute inset-0 bg-gradient-to-br from-blue-700/10 to-blue-800/10 rounded-3xl transform group-hover:scale-105 transition-transform duration-500"></div>
          <div class="relative bg-white/80 backdrop-blur-sm rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500 transform group-hover:-translate-y-4 border border-blue-200/50 overflow-hidden w-full flex flex-col flex-1">
            <!-- Header -->
            <div class="p-8 text-center border-b border-blue-200/50 flex-shrink-0 flex flex-col items-center justify-center">
              <div class="w-24 h-24 bg-gradient-to-br from-blue-700 to-blue-900 rounded-2xl flex items-center justify-center mb-16 transform transition-all duration-500 group-hover:scale-110 group-hover:rotate-6 shadow-lg">
                <span class="text-3xl text-white">⭐</span>
              </div>
              <h3 class="text-2xl font-black text-gray-800 mb-4">Pro</h3>
              <p class="text-gray-500 font-semibold">Negocios en Crecimiento</p>
            </div>
            
            <!-- Price -->
            <div class="p-6 bg-gradient-to-r from-blue-100 to-blue-200 text-center flex-shrink-0">
              <div class="text-4xl font-black text-gray-800 mb-1">$999.999</div>
              <div class="text-gray-500 text-sm">Pago único • E-commerce Básico</div>
            </div>
            
            <!-- Features -->
            <div class="p-6 flex-grow">
              <ul class="space-y-4">
                <li v-for="(feature, index) in professionalFeatures" :key="index" 
                    class="flex items-center transform transition-all duration-300 group-hover:translate-x-2">
                  <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center mr-4 flex-shrink-0 group-hover:bg-blue-200 transition-colors duration-300">
                    <span class="text-blue-500 text-lg">✓</span>
                  </div>
                  <span class="text-gray-600 font-medium text-left">{{ feature }}</span>
                </li>
              </ul>
            </div>
            
            <!-- CTA -->
            <div class="p-6 pt-0 flex-shrink-0">
              <button class="w-full bg-gradient-to-r from-blue-700 to-blue-900 hover:from-blue-800 hover:to-blue-950 text-white font-bold py-4 px-6 rounded-xl transition-all duration-500 transform hover:scale-105 shadow-lg hover:shadow-xl relative overflow-hidden group">
                <span class="relative z-10">Ir Pro</span>
                <div class="absolute inset-0 bg-white/20 transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left"></div>
              </button>
            </div>
          </div>
        </div>

        <!-- Plan Empresa -->
        <div class="group relative w-full max-w-sm flex flex-col">
          <div class="absolute inset-0 bg-gradient-to-br from-blue-800/10 to-blue-900/10 rounded-3xl transform group-hover:scale-105 transition-transform duration-500"></div>
          <div class="relative bg-white/80 backdrop-blur-sm rounded-3xl shadow-2xl hover:shadow-3xl transition-all duration-500 transform group-hover:-translate-y-4 border border-blue-200/50 overflow-hidden w-full flex flex-col flex-1">
            <!-- Header -->
            <div class="p-8 text-center border-b border-blue-200/50 flex-shrink-0 flex flex-col items-center justify-center">
              <div class="w-24 h-24 bg-gradient-to-br from-blue-800 to-blue-950 rounded-2xl flex items-center justify-center mb-16 transform transition-all duration-500 group-hover:scale-110 group-hover:rotate-6 shadow-lg">
                <span class="text-3xl text-white">🏢</span>
              </div>
              <h3 class="text-2xl font-black text-gray-800 mb-4">Enterprise</h3>
              <p class="text-gray-500 font-semibold">Soluciones Corporativas</p>
            </div>
            
            <!-- Price -->
            <div class="p-6 bg-gradient-to-r from-blue-200 to-blue-300 text-center flex-shrink-0">
              <div class="text-4xl font-black text-gray-800 mb-1">$1.999.999</div>
              <div class="text-gray-500 text-sm">Pago único • Soporte 24/7</div>
            </div>
            
            <!-- Features -->
            <div class="p-6 flex-grow">
              <ul class="space-y-4">
                <li v-for="(feature, index) in enterpriseFeatures" :key="index" 
                    class="flex items-center transform transition-all duration-300 group-hover:translate-x-2">
                  <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center mr-4 flex-shrink-0 group-hover:bg-blue-200 transition-colors duration-300">
                    <span class="text-blue-500 text-lg">✓</span>
                  </div>
                  <span class="text-gray-600 font-medium text-left">{{ feature }}</span>
                </li>
              </ul>
            </div>
            
            <!-- CTA -->
            <div class="p-6 pt-0 flex-shrink-0">
              <button class="w-full bg-gradient-to-r from-blue-800 to-blue-950 hover:from-blue-900 hover:to-black text-white font-bold py-4 px-6 rounded-xl transition-all duration-500 transform hover:scale-105 shadow-lg hover:shadow-xl relative overflow-hidden group">
                <span class="relative z-10">Solicitar Demo</span>
                <div class="absolute inset-0 bg-white/20 transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left"></div>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const basicFeatures = [
  '5 páginas web premium',
  'Diseño responsive avanzado',
  'Formularios de contacto inteligentes',
  'SEO básico optimizado',
  'Hosting premium 1 año incluido',
  'Certificado SSL gratuito'
];

const standardFeatures = [
  '10 páginas web personalizadas',
  'Diseño UX/UI exclusivo',
  'Blog corporativo integrado',
  'SEO avanzado + Analytics',
  'Integración redes sociales',
  'Backup automático mensual'
];

const professionalFeatures = [
  'Páginas ilimitadas',
  'Diseño premium personalizado',
  'E-commerce básico integrado',
  'CMS personalizado',
  'Soporte prioritario 12/7',
  'Mantenimiento 6 meses'
];

const enterpriseFeatures = [
  'Desarrollo completamente a medida',
  'E-commerce avanzado escalable',
  'Integración API personalizada',
  'Soporte técnico 24/7 dedicado',
  'Mantenimiento anual incluido',
  'Consultoría estratégica digital'
];

const scrollToSection = (sectionId) => {
  const element = document.getElementById(sectionId);
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' });
  }
};
</script>