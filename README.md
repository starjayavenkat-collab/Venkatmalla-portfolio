import { Helmet } from "react-helmet-async";
import Navigation from "@/components/Navigation";
import Hero from "@/components/Hero";
import About from "@/components/About";
import Skills from "@/components/Skills";
import Experience from "@/components/Experience";
import Certifications from "@/components/Certifications";
import Projects from "@/components/Projects";
import Contact from "@/components/Contact";
import Footer from "@/components/Footer";

const Index = () => {
  return (
    <>
      <Helmet>
        <title>Venkat Malla | Senior Salesforce Developer</title>
        <meta
          name="description"
          content="Senior Salesforce Developer with 6+ years of experience in Apex, Lightning Web Components, REST/SOAP APIs, and CI/CD automation. 6x Salesforce Certified including Platform Developer I and AI Specialist."
        />
        <meta
          name="keywords"
          content="Salesforce Developer, Apex, Lightning Web Components, LWC, Salesforce Administrator, Copado, CI/CD, REST API, SOAP API, Platform Developer, Salesforce Certified, Tampa Florida"
        />
        <meta property="og:title" content="Venkat Malla | Senior Salesforce Developer" />
        <meta
          property="og:description"
          content="Senior Salesforce Developer with 6+ years building enterprise-scale CRM solutions. Expert in Apex, LWC, integrations, and DevOps."
        />
        <meta property="og:type" content="website" />
        <link rel="canonical" href="https://venkatmalla.com" />
      </Helmet>

      <main className="min-h-screen">
        <Navigation />
        <Hero />
        <About />
        <Skills />
        <Experience />
        <Certifications />
        <Projects />
        <Contact />
        <Footer />
      </main>
    </>
  );
};

export default Index;
