import React from "react";

export default function OrakelMindmap() {
  return (
    <div className="p-8 w-full max-w-4xl mx-auto">
      <div className="text-center mb-6">
        <h1 className="text-4xl font-bold">Orakel</h1>
        <h2 className="text-2xl font-semibold">Thomas Olde Heuvelt</h2>
        <img src="/images/orakel_cover.jpg" alt="Boekcover Orakel" className="mx-auto my-4 w-48" />
      </div>
      
      <div className="grid grid-cols-2 gap-6">
        <div className="p-4 border-l-4 border-orange-500 bg-orange-100 rounded">
          <h2 className="text-xl font-semibold">Plot</h2>
          <img src="/images/plot_icon.png" alt="Plot" className="w-12 mb-2" />
          <ul className="list-disc ml-5">
            <li>Emma en Luca vinden het mysterieuze schip.</li>
            <li>Emma verdwijnt nadat ze aan boord gaat.</li>
            <li>Onderzoek door geheime dienst November-6.</li>
            <li>Het schip blijkt een gevaarlijk fenomeen te zijn.</li>
          </ul>
        </div>
        
        <div className="p-4 border-l-4 border-green-500 bg-green-100 rounded">
          <h2 className="text-xl font-semibold">Personages</h2>
          <img src="/images/characters_icon.png" alt="Personages" className="w-12 mb-2" />
          <ul className="list-disc ml-5">
            <li><strong>Luca Wolf</strong> - 13-jarige jongen, hoofdpersonage.</li>
            <li><strong>Emma Reich</strong> - Luca's vriendin, verdwijnt in het schip.</li>
            <li><strong>Grim</strong> - Onderzoeker, belangrijke rol in het mysterie.</li>
            <li><strong>November-6</strong> - Geheime dienst die de zaak onderzoekt.</li>
          </ul>
        </div>
        
        <div className="p-4 border-l-4 border-purple-500 bg-purple-100 rounded">
          <h2 className="text-xl font-semibold">Perspectief</h2>
          <img src="/images/perspective_icon.png" alt="Perspectief" className="w-12 mb-2" />
          <p>Wisselend perspectief tussen Luca en Grim, alwetende verteller.</p>
        </div>
        
        <div className="p-4 border-l-4 border-blue-500 bg-blue-100 rounded">
          <h2 className="text-xl font-semibold">Tijd</h2>
          <img src="/images/time_icon.png" alt="Tijd" className="w-12 mb-2" />
          <p>Speelt zich af in het heden met flashbacks naar de geschiedenis van het schip.</p>
        </div>
        
        <div className="p-4 border-l-4 border-yellow-500 bg-yellow-100 rounded">
          <h2 className="text-xl font-semibold">Ruimte</h2>
          <img src="/images/space_icon.png" alt="Ruimte" className="w-12 mb-2" />
          <ul className="list-disc ml-5">
            <li>Kustdorp</li>
            <li>Bollenvelden</li>
            <li>Het mysterieuze schip</li>
          </ul>
        </div>
        
        <div className="p-4 border-l-4 border-red-500 bg-red-100 rounded">
          <h2 className="text-xl font-semibold">Symbolen</h2>
          <img src="/images/symbols_icon.png" alt="Symbolen" className="w-12 mb-2" />
          <ul className="list-disc ml-5">
            <li><strong>Het schip</strong> - symbool voor het onbekende en gevaar.</li>
            <li><strong>De mist</strong> - symbool voor onzekerheid en geheimen.</li>
            <li><strong>De scheepsbel</strong> - symbool voor het lot.</li>
          </ul>
        </div>
        
        <div className="p-4 border-l-4 border-pink-500 bg-pink-100 rounded">
          <h2 className="text-xl font-semibold">Motieven</h2>
          <img src="/images/motifs_icon.png" alt="Motieven" className="w-12 mb-2" />
          <ul className="list-disc ml-5">
            <li>Verdwijningen</li>
            <li>Het bovennatuurlijke</li>
            <li>Geheimhouding en complotten</li>
            <li>De strijd tussen weten en niet-weten</li>
          </ul>
        </div>
        
        <div className="p-4 border-l-4 border-gray-500 bg-gray-100 rounded">
          <h2 className="text-xl font-semibold">Thema</h2>
          <img src="/images/theme_icon.png" alt="Thema" className="w-12 mb-2" />
          <p>De gevolgen van nieuwsgierigheid, de invloed van het verleden op het heden, goed versus kwaad.</p>
        </div>
      </div>
    </div>
  );
}
