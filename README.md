import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function DentalRCM() {
  return (
    <div className="min-h-screen bg-white text-gray-800 p-8">
      <header className="text-center mb-12">
        <h1 className="text-4xl font-bold mb-2">Dental RCM Services</h1>
        <p className="text-lg">Specializing in Insurance Verification</p>
      </header>

      <section className="grid grid-cols-1 md:grid-cols-2 gap-6 mb-12">
        <Card className="rounded-2xl shadow-lg">
          <CardContent className="p-6">
            <h2 className="text-2xl font-semibold mb-4">What We Do</h2>
            <p>
              We provide dedicated dental insurance verification services for U.S.-based dental offices. Our team ensures accurate, real-time benefit verification to minimize claim denials and improve patient experience.
            </p>
          </CardContent>
        </Card>

        <Card className="rounded-2xl shadow-lg">
          <CardContent className="p-6">
            <h2 className="text-2xl font-semibold mb-4">Why Choose Us?</h2>
            <ul className="list-disc list-inside space-y-2">
              <li>24-48 hour turnaround time</li>
              <li>HIPAA-compliant processes</li>
              <li>Expert team trained in U.S. dental insurance</li>
              <li>Customizable verification templates</li>
            </ul>
          </CardContent>
        </Card>
      </section>

      <section className="mb-12">
        <Card className="rounded-2xl shadow-lg">
          <CardContent className="p-6">
            <h2 className="text-2xl font-semibold mb-4">Our Verification Process</h2>
            <ol className="list-decimal list-inside space-y-2">
              <li>Receive patient schedule from the clinic.</li>
              <li>Contact insurance provider or check via portal.</li>
              <li>Verify coverage, benefits, waiting period, and exclusions.</li>
              <li>Update verification sheet with accurate information.</li>
              <li>Send report to clinic before appointment day.</li>
            </ol>
          </CardContent>
        </Card>
      </section>

      <section className="text-center">
        <h2 className="text-2xl font-semibold mb-4">Start With Us</h2>
        <p className="mb-6">Get in touch today and streamline your dental insurance verification process.</p>
        <Button className="text-white bg-blue-600 hover:bg-blue-700 rounded-full px-6 py-2 text-lg">
          Contact Us
        </Button>
      </section>
    </div>
  );
}
