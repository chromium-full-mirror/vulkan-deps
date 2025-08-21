# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f3a7f2c2bc48b20510cc76ac8479ce882bbe2032',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a906345b8a7bccc416b006b2048e13f40d9b2327',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'a8637796c28386c3cf3b4e8107020fbb52c46f3f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '7318ab44eb5e98040abf9460e2d5bb7f719becaa',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2efaa559ff41655ece68b2e904e2bb7e7d55d265',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '484f3cd7dfb13f63a8b8930cb0397e9b849ab076',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0eb12b4ea70b15be6a10f6212c1633e5c9ce0cca',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4f4c0b6c61223b703f1c753a404578d7d63932ad',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '58279ecc841699c9a1171fedc7f38ed8c195bfb2',
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
