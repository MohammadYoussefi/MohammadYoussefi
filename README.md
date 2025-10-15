import { Github, Sparkles } from "lucide-react";

export const Header = () => {
  return (
    <header className="border-b border-primary/20 bg-card/50 backdrop-blur-sm sticky top-0 z-50">
      <div className="container mx-auto px-4 py-4">
        <div className="flex items-center justify-between">
          <div className="flex items-center gap-3">
            <div className="relative">
              <Github className="w-8 h-8 text-primary" />
              <Sparkles className="w-4 h-4 text-accent absolute -top-1 -right-1 animate-pulse" />
            </div>
            <div>
              <h1 className="text-2xl font-bold bg-gradient-to-r from-primary via-accent to-primary bg-clip-text text-transparent animate-gradient">
                GitHub README Designer
              </h1>
              <p className="text-sm text-muted-foreground">
                Professional README design for your GitHub profile
              </p>
            </div>
          </div>
          <div className="hidden md:flex items-center gap-2">
            <div className="px-4 py-2 rounded-full bg-primary/10 border border-primary/20">
              <span className="text-sm text-primary font-medium">✨ Advanced Version</span>
            </div>
          </div>
        </div>
      </div>
    </header>
  );
};
