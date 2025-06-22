export default function LandingPage() {
  return (
    <div className="bg-[#002b5c] text-white font-sans">
      {/* Hero Section */}
      <section className="text-center py-16 px-6">
        <h1 className="text-4xl md:text-5xl font-bold mb-4">Learning Reimagined, for every student.</h1>
        <p className="text-lg md:text-xl mb-6">
          AI-Powered. Immersive. Personalized. Empower your child or classroom with lessons that adapt to how they learn best—delivered through cutting-edge AI and engaging virtual simulations.
        </p>
        <div className="flex flex-col md:flex-row justify-center items-center space-y-4 md:space-y-0 md:space-x-6">
          
          <button className="bg-[#3dbb75] text-black px-6 py-3 rounded-2xl shadow-md">Watch Demo</button>
        </div>
      </section>

      {/* Problem & Solution Section */}
      <section className="py-16 px-6">
        <h2 className="text-3xl font-bold text-center mb-6">Education isn’t one-size-fits-all. Why should learning be?</h2>
        <div className="max-w-3xl mx-auto text-center space-y-4">
          <p>One-size-fits-all education leaves diverse learners behind.</p>
          <p className="mt-6 font-semibold">ASURI solves this by:</p>
          <ul className="list-inside text-[#3dbb75]">
  <li className="before:content-['✓'] before:mr-2 before:text-[#3dbb75] before:font-bold">Using AI to adapt lessons to each student</li>
  <li className="before:content-['✓'] before:mr-2 before:text-[#3dbb75] before:font-bold">Delivering immersive, hands-on learning via VR</li>
  <li className="before:content-['✓'] before:mr-2 before:text-[#3dbb75] before:font-bold">Empowering teachers with smart tools, feedback, and insights</li>
</ul>
        </div>
      </section>

      {/* How It Works */}
      <section className="bg-[#0a3c66] py-16 px-6 text-center">
        <h2 className="text-3xl font-bold mb-10">How It Works</h2>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-10 max-w-5xl mx-auto">
          <div>
            <h3 className="text-xl font-semibold mb-2 text-[#3dbb75]">1. Create a Student Profile</h3>
            <p>Teachers and parents input key learning data to personalize instruction.</p>
          </div>
          <div>
            <h3 className="text-xl font-semibold mb-2 text-[#3dbb75]">2. Generate Custom Lessons</h3>
            <p>AI curates dynamic lessons tailored to each student's strengths and challenges.</p>
          </div>
          <div>
            <h3 className="text-xl font-semibold mb-2 text-[#3dbb75]">3. Learn, Track & Improve</h3>
            <p>Students learn through simulations while teachers receive real-time feedback and progress reports.</p>
          </div>
        </div>
      </section>

      {/* Who It's For */}
      <section className="py-16 px-6 text-center">
        <h2 className="text-3xl font-bold mb-10">Built for Every Learner</h2>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-10 max-w-5xl mx-auto">
          <div>
            <h3 className="text-xl font-semibold mb-2 text-[#3dbb75]">Teachers</h3>
            <p>Save time and teach 30 different students, 30 different ways.</p>
          </div>
          <div>
            <h3 className="text-xl font-semibold mb-2 text-[#3dbb75]">Schools</h3>
            <p>Scalable support for resource-challenged classrooms worldwide.</p>
          </div>
          <div>
            <h3 className="text-xl font-semibold mb-2 text-[#3dbb75]">Parents & Homeschoolers</h3>
            <p>Make learning exciting and effective at home or on the go.</p>
          </div>
        </div>
      </section>

      {/* Final CTA */}
      <section className="bg-[#3dbb75] text-white text-center py-16 px-6">
        <h2 className="text-3xl font-bold mb-4">Learning, personalized.</h2>
        <p className="text-lg mb-6">No child should be left behind.</p>
        <div className="space-x-4">
          <button className="bg-[#002b5c] text-white px-6 py-3 rounded-2xl">Join the Waitlist</button>
          <button className="bg-[#002b5c] text-white px-6 py-3 rounded-2xl">Watch Demo</button>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-[#002b5c] text-center py-6 text-sm">
        <p>© {new Date().getFullYear()} ASURI. All rights reserved.</p>
        <div className="mt-2 space-x-4">
          <a href="#" className="hover:underline">About</a>
          <a href="#" className="hover:underline">Contact</a>
          <a href="#" className="hover:underline">Privacy</a>
          <a href="#" className="hover:underline">Terms</a>
        </div>
      </footer>
    </div>
  );
}
