# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'fcf4e9296fa400e2b03c34e23b261e0c8a0ac34d',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '68daa9bc0602e057a36c83fe4dcc441c9bd38447',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'a8637796c28386c3cf3b4e8107020fbb52c46f3f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '925b0bd1eeb3ea1ceb18e2bb5929575b0cfb3f67',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2efaa559ff41655ece68b2e904e2bb7e7d55d265',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '484f3cd7dfb13f63a8b8930cb0397e9b849ab076',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0eb12b4ea70b15be6a10f6212c1633e5c9ce0cca',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4f4c0b6c61223b703f1c753a404578d7d63932ad',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6dc22e91026ed41d069c4d28bc81e906377287f6',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
