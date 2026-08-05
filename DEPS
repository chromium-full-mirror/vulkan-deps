# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2ee090f606ace31e07f584b1c1b9ddf4909ce202',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'fa705f5c11aacd29abc9733591e9697e015a145b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '27009dcaecd266ea7fb969bca44ebc87dcdc6269',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f589ef005c49f6f19c8e78eb5269104ba293beb4',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '11d6898377797e07dbd543aaaa367e4465074597',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '160db0eeff25e908fae891ec2df861fc6f8e26d3',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2ca98085c06deeec789fb1c18e95f66803bdaddb',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'bf60ee138ced6a8cf9bc3d3f05e32c6a99c2e778',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '0837e8e7d934ee5e7a56444b245d144a9d48b86a',
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
