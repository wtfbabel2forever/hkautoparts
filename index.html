import React, { useState, useEffect } from 'react';

const App = () => {
  const [currentSection, setCurrentSection] = useState('home');
  const [isMenuOpen, setIsMenuOpen] = useState(false);

  const featuredProducts = [
    {
      id: 1,
      name: "2018 Honda Civic Engine",
      price: "$2,499",
      condition: "Used - Excellent",
      image: "https://placehold.co/400x300/2563eb/ffffff?text=Honda+Civic+Engine",
      description: "Low mileage, professionally inspected and tested. Comes with 90-day warranty."
    },
    {
      id: 2,
      name: "2020 Toyota Camry Transmission",
      price: "$1,899",
      condition: "Used - Good",
      image: "https://placehold.co/400x300/1f2937/ffffff?text=Toyota+Camry+Transmission",
      description: "Fully rebuilt transmission with new seals and gaskets. Includes installation guide."
    },
    {
      id: 3,
      name: "2019 Ford F-150 Headlights",
      price: "$399",
      condition: "Used - Like New",
      image: "https://placehold.co/400x300/dc2626/ffffff?text=Ford+F-150+Headlights",
      description: "Original equipment manufacturer (OEM) headlights with LED technology. No scratches."
    },
    {
      id: 4,
      name: "2017 Chevrolet Silverado Suspension Kit",
      price: "$1,299",
      condition: "Used - Excellent",
      image: "https://placehold.co/400x300/059669/ffffff?text=Chevy+Silverado+Suspension",
      description: "Complete suspension system including shocks, struts, and springs. Professional install recommended."
    }
  ];

  const testimonials = [
    {
      name: "Mike R.",
      rating: 5,
      text: "Found the perfect engine for my project car at a fraction of the cost of new parts. Fast shipping and excellent communication!"
    },
    {
      name: "Sarah L.",
      rating: 5,
      text: "The quality of the parts exceeded my expectations. The warranty gave me peace of mind. Will definitely buy again!"
    },
    {
      name: "James T.",
      rating: 4,
      text: "Great selection of used auto parts. Customer service was responsive and knowledgeable about compatibility issues."
    }
  ];

  const navigation = [
    { id: 'home', label: 'Home' },
    { id: 'inventory', label: 'Inventory' },
    { id: 'ebay', label: 'eBay Store' },
    { id: 'about', label: 'About Us' },
    { id: 'contact', label: 'Contact' }
  ];

  const scrollToSection = (sectionId) => {
    setCurrentSection(sectionId);
    setIsMenuOpen(false);
    document.getElementById(sectionId)?.scrollIntoView({ behavior: 'smooth' });
  };

  return (
    <div className="min-h-screen bg-gray-50">
      {/* Navigation */}
      <nav className="bg-white shadow-lg fixed w-full z-50">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex justify-between h-16">
            <div className="flex items-center">
              <div className="flex-shrink-0 flex items-center">
                <div className="w-10 h-10 bg-gradient-to-r from-blue-600 to-indigo-700 rounded-lg flex items-center justify-center">
                  <span className="text-white font-bold text-xl">LA</span>
                </div>
                <span className="ml-3 text-2xl font-bold text-gray-900">LA Auto Parts</span>
              </div>
            </div>
            
            {/* Desktop Navigation */}
            <div className="hidden md:flex items-center space-x-8">
              {navigation.map((item) => (
                <button
                  key={item.id}
                  onClick={() => scrollToSection(item.id)}
                  className={`text-sm font-medium transition-colors duration-200 ${
                    currentSection === item.id 
                      ? 'text-blue-600 border-b-2 border-blue-600' 
                      : 'text-gray-700 hover:text-blue-600'
                  }`}
                >
                  {item.label}
                </button>
              ))}
              <a href="https://www.ebay.com" target="_blank" rel="noopener noreferrer" className="bg-blue-600 text-white px-6 py-2 rounded-full text-sm font-medium hover:bg-blue-700 transition-colors duration-200">
                eBay Store
              </a>
            </div>

            {/* Mobile menu button */}
            <div className="md:hidden flex items-center">
              <button
                onClick={() => setIsMenuOpen(!isMenuOpen)}
                className="text-gray-700 hover:text-blue-600 focus:outline-none"
              >
                <svg className="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  {isMenuOpen ? (
                    <path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M6 18L18 6M6 6l12 12" />
                  ) : (
                    <path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M4 6h16M4 12h16M4 18h16" />
                  )}
                </svg>
              </button>
            </div>
          </div>
        </div>

        {/* Mobile Navigation Menu */}
        {isMenuOpen && (
          <div className="md:hidden bg-white border-t border-gray-200">
            <div className="px-2 pt-2 pb-3 space-y-1">
              {navigation.map((item) => (
                <button
                  key={item.id}
                  onClick={() => scrollToSection(item.id)}
                  className="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50 w-full text-left"
                >
                  {item.label}
                </button>
              ))}
              <a
                href="https://www.ebay.com"
                target="_blank"
                rel="noopener noreferrer"
                className="block px-3 py-2 rounded-md text-base font-medium bg-blue-600 text-white text-center hover:bg-blue-700"
              >
                eBay Store
              </a>
            </div>
          </div>
        )}
      </nav>

      {/* Hero Section */}
      <section id="home" className="pt-16 bg-gradient-to-r from-blue-900 via-blue-800 to-indigo-900 text-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 text-center">
          <h1 className="text-4xl md:text-6xl font-bold mb-6">
            Premium Used Auto Parts
          </h1>
          <p className="text-xl md:text-2xl mb-8 opacity-90 max-w-3xl mx-auto">
            Serving Southern California since 2010 with high-quality, inspected used auto parts at unbeatable prices.
          </p>
          <div className="flex flex-col sm:flex-row gap-4 justify-center">
            <button
              onClick={() => scrollToSection('inventory')}
              className="bg-white text-blue-900 px-8 py-3 rounded-full font-semibold text-lg hover:bg-gray-100 transform hover:scale-105 transition-all duration-200 shadow-lg"
            >
              Browse Inventory
            </button>
            <button
              onClick={() => scrollToSection('ebay')}
              className="border-2 border-white text-white px-8 py-3 rounded-full font-semibold text-lg hover:bg-white hover:text-blue-900 transform hover:scale-105 transition-all duration-200"
            >
              Visit eBay Store
            </button>
          </div>
        </div>
        
        {/* Decorative elements */}
        <div className="absolute top-20 right-10 w-20 h-20 bg-blue-600 rounded-full opacity-20 animate-pulse"></div>
        <div className="absolute bottom-20 left-10 w-32 h-32 bg-indigo-600 rounded-full opacity-20 animate-pulse delay-1000"></div>
      </section>

      {/* Inventory Section */}
      <section id="inventory" className="py-20 bg-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Featured Inventory</h2>
            <p className="text-xl text-gray-600 max-w-3xl mx-auto">
              We source only the highest quality used automotive parts from reliable suppliers across Southern California.
            </p>
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            {featuredProducts.map((product) => (
              <div key={product.id} className="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300 transform hover:-translate-y-1">
                <img 
                  src={product.image} 
                  alt={product.name} 
                  className="w-full h-48 object-cover"
                />
                <div className="p-6">
                  <h3 className="text-xl font-bold text-gray-900 mb-2">{product.name}</h3>
                  <p className="text-blue-600 font-bold text-lg mb-2">{product.price}</p>
                  <p className="text-sm text-gray-600 mb-4 bg-green-100 text-green-800 px-2 py-1 inline-block rounded-full">
                    {product.condition}
                  </p>
                  <p className="text-gray-700 text-sm mb-6">{product.description}</p>
                  <button className="w-full bg-blue-600 text-white py-2 rounded-lg font-medium hover:bg-blue-700 transition-colors duration-200">
                    View Details
                  </button>
                </div>
              </div>
            ))}
          </div>
          
          <div className="text-center mt-12">
            <button className="bg-gray-100 text-gray-800 px-8 py-3 rounded-full font-semibold hover:bg-gray-200 transition-colors duration-200">
              View All Inventory
            </button>
          </div>
        </div>
      </section>

      {/* eBay Store Section */}
      <section id="ebay" className="py-20 bg-gray-50">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Our eBay Store</h2>
            <p className="text-xl text-gray-600 max-w-3xl mx-auto">
              We're proud sellers on eBay with over 5,000+ satisfied customers and a 99.8% positive feedback rating.
            </p>
          </div>
          
          <div className="flex flex-col lg:flex-row items-center gap-12">
            <div className="lg:w-1/2">
              <img 
                src="https://placehold.co/600x400/f97316/ffffff?text=eBay+Store+Screenshot" 
                alt="eBay Store" 
                className="rounded-xl shadow-lg"
              />
            </div>
            <div className="lg:w-1/2">
              <div className="bg-white p-8 rounded-xl shadow-lg">
                <div className="flex items-center mb-6">
                  <svg className="w-8 h-8 text-yellow-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.922-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                  </svg>
                  <h3 className="text-2xl font-bold text-gray-900">eBay Top Rated Seller</h3>
                </div>
                
                <ul className="space-y-4 mb-8">
                  <li className="flex items-start">
                    <svg className="w-5 h-5 text-green-500 mt-0.5 mr-3 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fillRule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-8.707l-3-3a1 1 0 00-1.414 0l-3 3a1 1 0 001.414 1.414L9 9.414V13a1 1 0 102 0V9.414l1.293 1.293a1 1 0 001.414-1.414z" clipRule="evenodd" />
                    </svg>
                    <span className="text-gray-700">Fast shipping from our Los Angeles warehouse</span>
                  </li>
                  <li className="flex items-start">
                    <svg className="w-5 h-5 text-green-500 mt-0.5 mr-3 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fillRule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-8.707l-3-3a1 1 0 00-1.414 0l-3 3a1 1 0 001.414 1.414L9 9.414V13a1 1 0 102 0V9.414l1.293 1.293a1 1 0 001.414-1.414z" clipRule="evenodd" />
                    </svg>
                    <span className="text-gray-700">Every part is inspected and tested before listing</span>
                  </li>
                  <li className="flex items-start">
                    <svg className="w-5 h-5 text-green-500 mt-0.5 mr-3 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fillRule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-8.707l-3-3a1 1 0 00-1.414 0l-3 3a1 1 0 001.414 1.414L9 9.414V13a1 1 0 102 0V9.414l1.293 1.293a1 1 0 001.414-1.414z" clipRule="evenodd" />
                    </svg>
                    <span className="text-gray-700">90-day warranty on all parts</span>
                  </li>
                  <li className="flex items-start">
                    <svg className="w-5 h-5 text-green-500 mt-0.5 mr-3 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
                      <path fillRule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-8.707l-3-3a1 1 0 00-1.414 0l-3 3a1 1 0 001.414 1.414L9 9.414V13a1 1 0 102 0V9.414l1.293 1.293a1 1 0 001.414-1.414z" clipRule="evenodd" />
                    </svg>
                    <span className="text-gray-700">Compatible parts guaranteed or your money back</span>
                  </li>
                </ul>
                
                <a 
                  href="https://www.ebay.com" 
                  target="_blank" 
                  rel="noopener noreferrer"
                  className="block w-full bg-red-600 text-white py-3 rounded-lg font-semibold text-center hover:bg-red-700 transition-colors duration-200"
                >
                  Visit Our eBay Store Now
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* About Section */}
      <section id="about" className="py-20 bg-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <div>
              <h2 className="text-3xl md:text-4xl font-bold text-gray-900 mb-6">About LA Auto Parts</h2>
              <p className="text-lg text-gray-600 mb-6">
                Founded in 2010 in Los Angeles, California, LA Auto Parts has become one of the region's most trusted sources for high-quality used automotive parts. 
                Our team of experts carefully inspects every component to ensure reliability and performance.
              </p>
              <p className="text-lg text-gray-600 mb-8">
                We specialize in sourcing parts from salvage yards across Southern California, ensuring we have the inventory you need when you need it. 
                From engines and transmissions to electrical components and body parts, we've got you covered.
              </p>
              
              <div className="grid grid-cols-2 gap-6 mb-8">
                <div className="text-center p-6 bg-gray-50 rounded-xl">
                  <div className="text-3xl font-bold text-blue-600 mb-2">5,000+</div>
                  <div className="text-gray-600">Satisfied Customers</div>
                </div>
                <div className="text-center p-6 bg-gray-50 rounded-xl">
                  <div className="text-3xl font-bold text-blue-600 mb-2">15+</div>
                  <div className="text-gray-600">Years Experience</div>
                </div>
              </div>
              
              <div className="flex space-x-4">
                <button className="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-blue-700 transition-colors duration-200">
                  Learn More
                </button>
                <button className="border-2 border-gray-300 text-gray-700 px-8 py-3 rounded-lg font-semibold hover:border-blue-600 hover:text-blue-600 transition-colors duration-200">
                  Contact Us
                </button>
              </div>
            </div>
            
            <div className="relative">
              <img 
                src="https://placehold.co/600x500/1f2937/ffffff?text=LA+Auto+Parts+Warehouse" 
                alt="LA Auto Parts Warehouse" 
                className="rounded-xl shadow-lg"
              />
              <div className="absolute -bottom-6 -left-6 bg-blue-600 text-white p-6 rounded-xl shadow-lg">
                <div className="text-2xl font-bold">📍 Los Angeles, CA</div>
                <div className="text-sm opacity-90">Serving all of Southern California</div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Testimonials Section */}
      <section className="py-20 bg-gray-50">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-3xl md:text-4xl font-bold text-gray-900 mb-4">What Our Customers Say</h2>
            <p className="text-xl text-gray-600">Trusted by thousands of car enthusiasts and mechanics</p>
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
            {testimonials.map((testimonial, index) => (
              <div key={index} className="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300">
                <div className="flex mb-4">
                  {[...Array(testimonial.rating)].map((_, i) => (
                    <svg key={i} className="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.922-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                    </svg>
                  ))}
                </div>
                <p className="text-gray-600 italic mb-6">"{testimonial.text}"</p>
                <div className="font-semibold text-gray-900">{testimonial.name}</div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section id="contact" className="py-20 bg-gray-900 text-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-3xl md:text-4xl font-bold mb-4">Get In Touch</h2>
            <p className="text-xl text-gray-300">Have questions about our inventory? Contact us today!</p>
          </div>
          
          <div className="grid grid-cols-1 lg:grid-cols-2 gap-12">
            <div>
              <h3 className="text-2xl font-bold mb-6">Visit Our Warehouse</h3>
              <div className="space-y-6">
                <div>
                  <h4 className="font-semibold text-lg mb-2">Address</h4>
                  <p className="text-gray-300">1234 Auto Parts Way<br />Los Angeles, CA 90001<br />United States</p>
                </div>
                
                <div>
                  <h4 className="font-semibold text-lg mb-2">Hours</h4>
                  <p className="text-gray-300">Monday - Friday: 8:00 AM - 6:00 PM<br />Saturday: 9:00 AM - 5:00 PM<br />Sunday: Closed</p>
                </div>
                
                <div>
                  <h4 className="font-semibold text-lg mb-2">Phone</h4>
                  <p className="text-gray-300">(213) 555-0123</p>
                </div>
                
                <div>
                  <h4 className="font-semibold text-lg mb-2">Email</h4>
                  <p className="text-gray-300">info@laautoparts.com</p>
                </div>
              </div>
              
              <div className="mt-12">
                <h4 className="font-semibold text-lg mb-4">Follow Us</h4>
                <div className="flex space-x-4">
                  <a href="#" className="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors duration-200">
                    <span className="text-sm font-bold">FB</span>
                  </a>
                  <a href="#" className="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors duration-200">
                    <span className="text-sm font-bold">IG</span>
                  </a>
                  <a href="#" className="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors duration-200">
                    <span className="text-sm font-bold">YT</span>
                  </a>
                </div>
              </div>
            </div>
            
            <div>
              <form className="space-y-6">
                <div>
                  <label htmlFor="name" className="block text-sm font-medium mb-2">Name</label>
                  <input 
                    type="text" 
                    id="name" 
                    className="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                    placeholder="Your name"
                  />
                </div>
                
                <div>
                  <label htmlFor="email" className="block text-sm font-medium mb-2">Email</label>
                  <input 
                    type="email" 
                    id="email" 
                    className="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                    placeholder="your@email.com"
                  />
                </div>
                
                <div>
                  <label htmlFor="subject" className="block text-sm font-medium mb-2">Subject</label>
                  <input 
                    type="text" 
                    id="subject" 
                    className="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                    placeholder="How can we help?"
                  />
                </div>
                
                <div>
                  <label htmlFor="message" className="block text-sm font-medium mb-2">Message</label>
                  <textarea 
                    id="message" 
                    rows={5}
                    className="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                    placeholder="Tell us about the part you're looking for..."
                  ></textarea>
                </div>
                
                <button 
                  type="submit"
                  className="w-full bg-blue-600 text-white py-3 rounded-lg font-semibold hover:bg-blue-700 transition-colors duration-200"
                >
                  Send Message
                </button>
              </form>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-800 text-white py-12">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center">
            <div className="flex items-center justify-center mb-4">
              <div className="w-8 h-8 bg-gradient-to-r from-blue-600 to-indigo-700 rounded-lg flex items-center justify-center mr-2">
                <span className="text-white font-bold text-sm">LA</span>
              </div>
              <span className="text-xl font-bold">LA Auto Parts</span>
            </div>
            <p className="text-gray-400 mb-6">
              © 2023 LA Auto Parts. All rights reserved. Serving Los Angeles and Southern California.
            </p>
            <div className="flex justify-center space-x-8 text-sm text-gray-400">
              <a href="#" className="hover:text-white transition-colors">Privacy Policy</a>
              <a href="#" className="hover:text-white transition-colors">Terms of Service</a>
              <a href="#" className="hover:text-white transition-colors">Shipping Information</a>
              <a href="#" className="hover:text-white transition-colors">Returns</a>
            </div>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default App;