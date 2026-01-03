# 🤝 Contributing to Optical Phenomena Simulations

Thank you for your interest in contributing! This document provides guidelines and information for contributors.

## 🌟 Ways to Contribute

### 🐛 Bug Reports
- Use the [bug report template](.github/ISSUE_TEMPLATE/bug_report.md)
- Include browser version, OS, and steps to reproduce
- Add screenshots or screen recordings if helpful

### 💡 Feature Requests
- Use the [feature request template](.github/ISSUE_TEMPLATE/feature_request.md)
- Describe the physics principle or educational value
- Include mockups or references if available

### 🔬 New Simulations
- Follow the [Simulation Development Guide](docs/SIMULATION_GUIDE.md)
- Ensure physics accuracy with proper citations
- Include interactive controls and educational content
- Add comprehensive tests

### 📖 Documentation
- Improve existing documentation
- Add new guides or tutorials
- Fix typos or unclear explanations
- Translate content to other languages

## 🚀 Getting Started

### 1. Fork and Clone
```bash
# Fork the repository on GitHub
# Then clone your fork
git clone https://github.com/yourusername/optical-phenomena-simulations.git
cd optical-phenomena-simulations
```

### 2. Set Up Development Environment
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Run tests
npm test
```

### 3. Create a Branch
```bash
# Create a feature branch
git checkout -b feature/your-feature-name

# Or a bugfix branch
git checkout -b bugfix/issue-number
```

## 📋 Development Guidelines

### Code Style
- Use consistent indentation (2 spaces)
- Follow HTML5 semantic markup
- Use modern JavaScript (ES6+)
- Comment complex physics calculations
- Keep functions small and focused

### Physics Accuracy
- Base simulations on established physics principles
- Include proper citations in code comments
- Validate equations with multiple sources
- Test edge cases and boundary conditions

### User Experience
- Ensure responsive design (mobile-first)
- Provide clear visual feedback
- Include helpful tooltips and labels
- Test accessibility features

### Performance
- Optimize animation loops
- Use requestAnimationFrame for smooth animations
- Minimize DOM manipulations
- Test on various devices and browsers

## 🧪 Testing

### Required Tests
- **Visual Tests**: Screenshots of key simulation states
- **Physics Tests**: Verify equation accuracy
- **Interaction Tests**: Test all user controls
- **Browser Tests**: Cross-browser compatibility

### Running Tests
```bash
npm test                    # All tests
npm run test:visual        # Visual regression
npm run test:physics       # Physics accuracy
npm run test:browser       # Cross-browser
```

## 📝 Pull Request Process

### 1. Before Submitting
- [ ] Code follows style guidelines
- [ ] All tests pass
- [ ] Documentation is updated
- [ ] Physics accuracy is verified
- [ ] Responsive design is tested

### 2. Pull Request Template
Use the [PR template](.github/PULL_REQUEST_TEMPLATE.md) and include:
- Clear description of changes
- Screenshots/videos of new features
- Physics validation references
- Testing checklist completion

### 3. Review Process
- Maintainers will review within 48 hours
- Address feedback promptly
- Keep discussions constructive
- Be patient with the review process

## 🎯 Simulation Development

### Physics Requirements
- Accurate mathematical models
- Real-world parameter ranges
- Proper units and scaling
- Educational value

### Technical Requirements
- Smooth 60fps animations
- Responsive controls
- Clear visual indicators
- Accessibility compliance

### Documentation Requirements
- Physics explanation
- User interaction guide
- Code documentation
- Test coverage

## 🏷️ Issue Labels

- `bug` - Something isn't working
- `enhancement` - New feature or improvement
- `documentation` - Documentation improvements
- `good first issue` - Good for newcomers
- `help wanted` - Extra attention needed
- `physics` - Physics accuracy issues
- `ui/ux` - User interface improvements
- `performance` - Performance optimizations

## 🎓 Educational Guidelines

### Target Audience
- High school physics students
- University undergraduates
- Self-learners and enthusiasts
- Educators and teachers

### Content Standards
- Age-appropriate explanations
- Progressive complexity
- Interactive learning elements
- Real-world applications

## 🌍 Community

### Communication Channels
- [GitHub Discussions](https://github.com/yourusername/optical-phenomena-simulations/discussions) - General discussion
- [Issues](https://github.com/yourusername/optical-phenomena-simulations/issues) - Bug reports and features
- [Discord Server](https://discord.gg/your-server) - Real-time chat
- [Twitter](https://twitter.com/yourhandle) - Updates and announcements

### Code of Conduct
- Be respectful and inclusive
- Focus on constructive feedback
- Help newcomers learn
- Maintain professional communication

## 🏆 Recognition

Contributors are recognized through:
- GitHub contributor graphs
- Credits in documentation
- Special badges for significant contributions
- Annual contributor highlights

## 📚 Resources

### Physics References
- Hecht, Eugene. "Optics" (5th Edition)
- Born, Max & Wolf, Emil. "Principles of Optics"
- Griffiths, David J. "Introduction to Quantum Mechanics"

### Development Resources
- [MDN Web Docs](https://developer.mozilla.org/)
- [Canvas API Reference](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [Physics Simulation Techniques](docs/PHYSICS_SIMULATION.md)

### Design Resources
- [Material Design Guidelines](https://material.io/design)
- [Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [Color Theory for Physics](docs/COLOR_THEORY.md)

## ❓ Questions?

If you have questions about contributing:
1. Check existing [discussions](https://github.com/yourusername/optical-phenomena-simulations/discussions)
2. Search [closed issues](https://github.com/yourusername/optical-phenomena-simulations/issues?q=is%3Aissue+is%3Aclosed)
3. Create a new discussion or issue
4. Contact maintainers directly

---

Thank you for contributing to physics education! 🔬✨